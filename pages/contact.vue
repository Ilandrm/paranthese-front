<template>
  <div>
    <!-- Hero Section -->
    <section class="bg-gradient-to-br from-emerald-50 to-teal-50 section-padding">
      <div class="container-custom">
        <div class="text-center mb-16">
          <h1 class="text-4xl lg:text-5xl font-bold text-gray-900 mb-6">
            Contactez-Nous
          </h1>
          <p class="text-xl text-gray-600 max-w-3xl mx-auto">
            Nous sommes là pour répondre à toutes vos questions et vous accompagner dans votre démarche
          </p>
        </div>
      </div>
    </section>

    <!-- Contact Form & Info -->
    <section class="bg-white section-padding">
      <div class="container-custom">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
          <!-- Formulaire de contact -->
          <div class="bg-gray-50 rounded-3xl p-8 lg:p-12">
            <h2 class="text-2xl lg:text-3xl font-bold text-gray-900 mb-8">
              Envoyez-nous un message
            </h2>
            
            <form @submit.prevent="submitForm" class="space-y-6">
              <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div>
                  <label for="firstName" class="block text-sm font-medium text-gray-700 mb-2">
                    Prénom *
                  </label>
                  <input
                    type="text"
                    id="firstName"
                    v-model="form.firstName"
                    required
                    class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-emerald-500 focus:border-emerald-500 transition-colors"
                    placeholder="Votre prénom"
                  >
                </div>
                <div>
                  <label for="lastName" class="block text-sm font-medium text-gray-700 mb-2">
                    Nom *
                  </label>
                  <input
                    type="text"
                    id="lastName"
                    v-model="form.lastName"
                    required
                    class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-emerald-500 focus:border-emerald-500 transition-colors"
                    placeholder="Votre nom"
                  >
                </div>
              </div>

              <div>
                <label for="email" class="block text-sm font-medium text-gray-700 mb-2">
                  Email *
                </label>
                <input
                  type="email"
                  id="email"
                  v-model="form.email"
                  required
                  class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-emerald-500 focus:border-emerald-500 transition-colors"
                  placeholder="votre@email.com"
                >
              </div>

              <div>
                <label for="phone" class="block text-sm font-medium text-gray-700 mb-2">
                  Téléphone
                </label>
                <input
                  type="tel"
                  id="phone"
                  v-model="form.phone"
                  class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-emerald-500 focus:border-emerald-500 transition-colors"
                  placeholder="06 12 34 56 78"
                >
              </div>

              <div>
                <label for="subject" class="block text-sm font-medium text-gray-700 mb-2">
                  Sujet *
                </label>
                <select
                  id="subject"
                  v-model="form.subject"
                  required
                  class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-emerald-500 focus:border-emerald-500 transition-colors"
                >
                  <option value="">Choisissez un sujet</option>
                  <option value="seminaire-collectif">Séminaire collectif</option>
                  <option value="accompagnement-individuel">Accompagnement individuel</option>
                  <option value="hebergement">Hébergement</option>
                  <option value="information">Demande d'information</option>
                  <option value="autre">Autre</option>
                </select>
              </div>

              <div>
                <label for="message" class="block text-sm font-medium text-gray-700 mb-2">
                  Message *
                </label>
                <textarea
                  id="message"
                  v-model="form.message"
                  required
                  rows="6"
                  class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-emerald-500 focus:border-emerald-500 transition-colors resize-none"
                  placeholder="Décrivez-nous votre demande, vos attentes ou vos questions..."
                ></textarea>
              </div>

              <div class="flex items-start space-x-3">
                <input
                  type="checkbox"
                  id="consent"
                  v-model="form.consent"
                  required
                  class="mt-1 h-4 w-4 text-emerald-600 focus:ring-emerald-500 border-gray-300 rounded"
                >
                <label for="consent" class="text-sm text-gray-600">
                  J'accepte que mes données personnelles soient utilisées pour traiter ma demande. 
                  <NuxtLink to="/mentions-legales" class="text-emerald-600 hover:text-emerald-700">
                    En savoir plus
                  </NuxtLink>
                </label>
              </div>

              <button
                type="submit"
                :disabled="isSubmitting"
                class="w-full btn-primary disabled:opacity-50 disabled:cursor-not-allowed"
              >
                <span v-if="!isSubmitting">Envoyer le message</span>
                <span v-else>Envoi en cours...</span>
              </button>
            </form>

            <div v-if="submitMessage" class="mt-6 p-4 rounded-lg" :class="submitSuccess ? 'bg-green-50 text-green-800' : 'bg-red-50 text-red-800'">
              {{ submitMessage }}
            </div>
          </div>

          <!-- Informations de contact -->
          <div class="space-y-8">
            <div>
              <h2 class="text-2xl lg:text-3xl font-bold text-gray-900 mb-8">
                Nos Coordonnées
              </h2>
              
              <div class="space-y-6">
                <div class="flex items-start space-x-4">
                  <div class="w-12 h-12 bg-emerald-600 rounded-full flex items-center justify-center flex-shrink-0">
                    <MapPinIcon class="h-6 w-6 text-white" />
                  </div>
                  <div>
                    <h3 class="font-semibold text-gray-900 mb-1">Adresse</h3>
                    <p class="text-gray-600">
                      123 Chemin de la Sérénité<br>
                      75000 Paris, France
                    </p>
                  </div>
                </div>

                <div class="flex items-start space-x-4">
                  <div class="w-12 h-12 bg-emerald-600 rounded-full flex items-center justify-center flex-shrink-0">
                    <PhoneIcon class="h-6 w-6 text-white" />
                  </div>
                  <div>
                    <h3 class="font-semibold text-gray-900 mb-1">Téléphone</h3>
                    <p class="text-gray-600">
                      <a href="tel:+33123456789" class="hover:text-emerald-600 transition-colors">
                        +33 1 23 45 67 89
                      </a>
                    </p>
                  </div>
                </div>

                <div class="flex items-start space-x-4">
                  <div class="w-12 h-12 bg-emerald-600 rounded-full flex items-center justify-center flex-shrink-0">
                    <EnvelopeIcon class="h-6 w-6 text-white" />
                  </div>
                  <div>
                    <h3 class="font-semibold text-gray-900 mb-1">Email</h3>
                    <p class="text-gray-600">
                      <a href="mailto:contact@parenthese-enchantee.com" class="hover:text-emerald-600 transition-colors">
                        contact@parenthese-enchantee.com
                      </a>
                    </p>
                  </div>
                </div>

                <div class="flex items-start space-x-4">
                  <div class="w-12 h-12 bg-emerald-600 rounded-full flex items-center justify-center flex-shrink-0">
                    <ClockIcon class="h-6 w-6 text-white" />
                  </div>
                  <div>
                    <h3 class="font-semibold text-gray-900 mb-1">Horaires d'accueil</h3>
                    <div class="text-gray-600 space-y-1">
                      <p>Lundi - Vendredi : 9h00 - 18h00</p>
                      <p>Samedi : 9h00 - 17h00</p>
                      <p>Dimanche : Sur rendez-vous</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- Réponse rapide -->
            <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-8">
              <h3 class="text-xl font-bold text-gray-900 mb-4">
                Besoin d'une réponse rapide ?
              </h3>
              <p class="text-gray-600 mb-6">
                Pour toute urgence ou question nécessitant une réponse immédiate, 
                n'hésitez pas à nous appeler directement.
              </p>
              <a 
                href="tel:+33123456789" 
                class="inline-flex items-center space-x-2 bg-emerald-600 hover:bg-emerald-700 text-white font-medium py-3 px-6 rounded-lg transition-colors duration-200"
              >
                <PhoneIcon class="h-5 w-5" />
                <span>Appeler maintenant</span>
              </a>
            </div>

            <!-- FAQ rapide -->
            <div class="bg-gray-50 rounded-2xl p-8">
              <h3 class="text-xl font-bold text-gray-900 mb-6">
                Questions Fréquentes
              </h3>
              <div class="space-y-4">
                <div>
                  <h4 class="font-semibold text-gray-900 mb-2">Combien de temps à l'avance réserver ?</h4>
                  <p class="text-gray-600 text-sm">Nous recommandons de réserver au moins 2 semaines à l'avance pour garantir votre place.</p>
                </div>
                <div>
                  <h4 class="font-semibold text-gray-900 mb-2">Proposez-vous des facilités de paiement ?</h4>
                  <p class="text-gray-600 text-sm">Oui, nous proposons des échelonnements de paiement selon votre situation.</p>
                </div>
                <div>
                  <h4 class="font-semibold text-gray-900 mb-2">Les séminaires sont-ils remboursés ?</h4>
                  <p class="text-gray-600 text-sm">Annulation gratuite jusqu'à 48h avant le début du séminaire.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
import { ref } from 'vue'
import { 
  MapPinIcon, 
  PhoneIcon, 
  EnvelopeIcon, 
  ClockIcon 
} from '@heroicons/vue/24/outline'

const form = ref({
  firstName: '',
  lastName: '',
  email: '',
  phone: '',
  subject: '',
  message: '',
  consent: false
})

const isSubmitting = ref(false)
const submitMessage = ref('')
const submitSuccess = ref(false)

const submitForm = async () => {
  isSubmitting.value = true
  submitMessage.value = ''
  
  try {
    // Simulation d'envoi de formulaire
    await new Promise(resolve => setTimeout(resolve, 1000))
    
    submitSuccess.value = true
    submitMessage.value = 'Votre message a été envoyé avec succès ! Nous vous répondrons dans les plus brefs délais.'
    
    // Reset form
    form.value = {
      firstName: '',
      lastName: '',
      email: '',
      phone: '',
      subject: '',
      message: '',
      consent: false
    }
  } catch (error) {
    submitSuccess.value = false
    submitMessage.value = 'Une erreur est survenue lors de l\'envoi. Veuillez réessayer ou nous contacter directement.'
  } finally {
    isSubmitting.value = false
  }
}

useHead({
  title: 'Contact - Parenthèse Enchantée',
  meta: [
    { name: 'description', content: 'Contactez Parenthèse Enchantée pour vos séminaires bien-être. Formulaire de contact, coordonnées et horaires d\'ouverture.' }
  ]
})
</script>