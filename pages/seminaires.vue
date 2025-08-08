<template>
  <div>
    <!-- Hero Section -->
    <section class="bg-gradient-to-br from-emerald-50 to-teal-50 section-padding">
      <div class="container-custom">
        <div class="text-center mb-16">
          <h1 class="text-4xl lg:text-5xl font-bold text-gray-900 mb-6">
            Nos Séminaires Bien-être
          </h1>
          <p class="text-xl text-gray-600 max-w-3xl mx-auto">
            Découvrez nos programmes conçus pour vous accompagner vers un mieux-être durable
          </p>
        </div>
      </div>
    </section>

    <!-- Seminaires Grid -->
    <section class="bg-white section-padding">
      <div class="container-custom">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 mb-16">
          <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-3xl p-8 lg:p-12">
            <div class="space-y-6">
              <div class="w-16 h-16 bg-emerald-600 rounded-full flex items-center justify-center">
                <UserGroupIcon class="h-8 w-8 text-white" />
              </div>
              <div>
                <h2 class="text-2xl lg:text-3xl font-bold text-gray-900 mb-4">
                  Séminaires Collectifs
                </h2>
                <p class="text-gray-600 text-lg leading-relaxed mb-6">
                  Rejoignez un groupe bienveillant pour partager votre expérience et bénéficier de la dynamique collective. 
                  Nos séminaires en groupe favorisent les échanges et créent des liens durables.
                </p>
                <div class="space-y-3 mb-8">
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-emerald-600" />
                    <span class="text-gray-700">Groupes de 8 à 12 participants maximum</span>
                  </div>
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-emerald-600" />
                    <span class="text-gray-700">Durée : 2 à 5 jours</span>
                  </div>
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-emerald-600" />
                    <span class="text-gray-700">Activités de groupe et temps individuels</span>
                  </div>
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-emerald-600" />
                    <span class="text-gray-700">Suivi post-séminaire inclus</span>
                  </div>
                </div>
                <div class="bg-white rounded-xl p-6 mb-6">
                  <h4 class="font-semibold text-gray-900 mb-3">Prochaines dates :</h4>
                  <div class="space-y-2 text-sm text-gray-600">
                    <p>• 15-17 Mars 2024 - Gestion du stress</p>
                    <p>• 22-24 Mars 2024 - Confiance en soi</p>
                    <p>• 5-7 Avril 2024 - Équilibre vie pro/perso</p>
                  </div>
                </div>
                <button class="btn-primary w-full">
                  Réserver un séminaire collectif
                </button>
              </div>
            </div>
          </div>

          <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-3xl p-8 lg:p-12">
            <div class="space-y-6">
              <div class="w-16 h-16 bg-blue-600 rounded-full flex items-center justify-center">
                <UserIcon class="h-8 w-8 text-white" />
              </div>
              <div>
                <h2 class="text-2xl lg:text-3xl font-bold text-gray-900 mb-4">
                  Accompagnement Individuel
                </h2>
                <p class="text-gray-600 text-lg leading-relaxed mb-6">
                  Bénéficiez d'un accompagnement sur-mesure, entièrement personnalisé selon vos besoins, 
                  vos objectifs et votre rythme. Un moment privilégié rien que pour vous.
                </p>
                <div class="space-y-3 mb-8">
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-blue-600" />
                    <span class="text-gray-700">Accompagnement 100% personnalisé</span>
                  </div>
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-blue-600" />
                    <span class="text-gray-700">Durée flexible : 1 à 7 jours</span>
                  </div>
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-blue-600" />
                    <span class="text-gray-700">Programme adapté à vos objectifs</span>
                  </div>
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-blue-600" />
                    <span class="text-gray-700">Disponibilité toute l'année</span>
                  </div>
                </div>
                <div class="bg-white rounded-xl p-6 mb-6">
                  <h4 class="font-semibold text-gray-900 mb-3">Thématiques disponibles :</h4>
                  <div class="space-y-2 text-sm text-gray-600">
                    <p>• Gestion du stress et des émotions</p>
                    <p>• Développement personnel</p>
                    <p>• Transition de vie</p>
                    <p>• Burn-out et récupération</p>
                  </div>
                </div>
                <button class="bg-blue-600 hover:bg-blue-700 text-white font-medium py-3 px-6 rounded-lg transition-colors duration-200 shadow-lg w-full">
                  Demander un accompagnement
                </button>
              </div>
            </div>
          </div>
        </div>

        <!-- Methodologie -->
        <div class="bg-gray-50 rounded-3xl p-8 lg:p-12">
          <div class="text-center mb-12">
            <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">
              Notre Méthodologie
            </h2>
            <p class="text-xl text-gray-600 max-w-3xl mx-auto">
              Une approche holistique qui combine différentes techniques pour un accompagnement complet
            </p>
          </div>

          <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="text-center">
              <div class="w-20 h-20 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
                <HeartIcon class="h-10 w-10 text-white" />
              </div>
              <h3 class="text-xl font-bold text-gray-900 mb-4">Écoute Bienveillante</h3>
              <p class="text-gray-600">
                Un espace sécurisé où vous pouvez vous exprimer librement, sans jugement, 
                dans une atmosphère de confiance et de respect.
              </p>
            </div>

            <div class="text-center">
              <div class="w-20 h-20 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
                <SparklesIcon class="h-10 w-10 text-white" />
              </div>
              <h3 class="text-xl font-bold text-gray-900 mb-4">Techniques Variées</h3>
              <p class="text-gray-600">
                Méditation, relaxation, exercices corporels, art-thérapie... 
                Nous adaptons nos outils selon vos préférences et besoins.
              </p>
            </div>

            <div class="text-center">
              <div class="w-20 h-20 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
                <AcademicCapIcon class="h-10 w-10 text-white" />
              </div>
              <h3 class="text-xl font-bold text-gray-900 mb-4">Outils Pratiques</h3>
              <p class="text-gray-600">
                Repartez avec des techniques concrètes que vous pourrez utiliser 
                au quotidien pour maintenir votre bien-être.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section class="bg-emerald-600 section-padding">
      <div class="container-custom text-center">
        <div class="max-w-3xl mx-auto space-y-8">
          <h2 class="text-3xl lg:text-4xl font-bold text-white">
            Prêt à commencer votre parcours ?
          </h2>
          <p class="text-xl text-emerald-100">
            Contactez-nous pour discuter de vos besoins et choisir le séminaire qui vous correspond
          </p>
          <div class="flex flex-col sm:flex-row gap-4 justify-center">
            <NuxtLink to="/contact" class="bg-white text-emerald-600 hover:bg-gray-50 font-medium py-3 px-8 rounded-lg transition-colors duration-200 shadow-lg">
              Nous contacter
            </NuxtLink>
            <a href="tel:+33123456789" class="bg-emerald-700 hover:bg-emerald-800 text-white font-medium py-3 px-8 rounded-lg transition-colors duration-200">
              Appeler maintenant
            </a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
import { 
  UserGroupIcon, 
  UserIcon, 
  CheckCircleIcon, 
  HeartIcon, 
  SparklesIcon, 
  AcademicCapIcon 
} from '@heroicons/vue/24/outline'

useHead({
  title: 'Séminaires - Parenthèse Enchantée',
  meta: [
    { name: 'description', content: 'Découvrez nos séminaires bien-être collectifs et individuels. Accompagnement personnalisé dans un cadre serein.' }
  ]
})
</script>