<template>
  <div>
    <!-- Hero Section -->
    <section class="bg-gradient-to-br from-emerald-50 to-teal-50 section-padding">
      <div class="container-custom">
        <div class="text-center mb-16">
          <h1 class="text-4xl lg:text-5xl font-bold text-gray-900 mb-6">
            À Propos de Nous
          </h1>
          <p class="text-xl text-gray-600 max-w-3xl mx-auto">
            Découvrez notre histoire, notre philosophie et l'équipe qui vous accompagne
          </p>
        </div>
      </div>
    </section>

    <!-- Notre Histoire -->
    <section class="bg-white section-padding">
      <div class="container-custom">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center mb-16">
          <div class="space-y-6">
            <h2 class="text-3xl lg:text-4xl font-bold text-gray-900">
              Notre Histoire
            </h2>
            <p class="text-lg text-gray-600 leading-relaxed">
              Parenthèse Enchantée est née d'une vision simple : créer un havre de paix où chacun peut 
              se reconnecter avec soi-même et retrouver son équilibre intérieur.
            </p>
            <p class="text-lg text-gray-600 leading-relaxed">
              Fondé en 2018 par une équipe de professionnels du bien-être, notre centre s'est développé 
              autour des valeurs de bienveillance, d'authenticité et de respect de chacun.
            </p>
            <p class="text-lg text-gray-600 leading-relaxed">
              Aujourd'hui, nous accueillons des centaines de personnes chaque année, toutes à la recherche 
              d'un moment de pause dans leur vie quotidienne pour se ressourcer et repartir plus sereines.
            </p>
          </div>
          <div class="relative">
            <div class="aspect-[4/3] bg-gradient-to-br from-emerald-200 to-teal-300 rounded-3xl shadow-2xl flex items-center justify-center">
              <div class="text-center text-white">
                <div class="w-24 h-24 bg-white/20 rounded-full flex items-center justify-center mx-auto mb-4">
                  <HeartIcon class="h-12 w-12" />
                </div>
                <p class="text-lg font-medium">6 ans d'accompagnement</p>
                <p class="text-sm opacity-90">Plus de 1000 personnes accompagnées</p>
              </div>
            </div>
          </div>
        </div>

        <!-- Notre Philosophie -->
        <div class="bg-gray-50 rounded-3xl p-8 lg:p-12 mb-16">
          <div class="text-center mb-12">
            <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">
              Notre Philosophie
            </h2>
            <p class="text-xl text-gray-600 max-w-3xl mx-auto">
              Une approche holistique centrée sur l'humain et le respect de chacun
            </p>
          </div>

          <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="text-center">
              <div class="w-20 h-20 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
                <HeartIcon class="h-10 w-10 text-white" />
              </div>
              <h3 class="text-xl font-bold text-gray-900 mb-4">Bienveillance</h3>
              <p class="text-gray-600">
                Nous créons un environnement sécurisé et bienveillant où chacun peut s'exprimer 
                librement et être accueilli sans jugement.
              </p>
            </div>

            <div class="text-center">
              <div class="w-20 h-20 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
                <UserIcon class="h-10 w-10 text-white" />
              </div>
              <h3 class="text-xl font-bold text-gray-900 mb-4">Personnalisation</h3>
              <p class="text-gray-600">
                Chaque personne est unique. Nous adaptons notre accompagnement à vos besoins, 
                votre rythme et vos objectifs personnels.
              </p>
            </div>

            <div class="text-center">
              <div class="w-20 h-20 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
                <SparklesIcon class="h-10 w-10 text-white" />
              </div>
              <h3 class="text-xl font-bold text-gray-900 mb-4">Authenticité</h3>
              <p class="text-gray-600">
                Nous privilégions les approches naturelles et authentiques, en harmonie 
                avec votre être profond et vos valeurs.
              </p>
            </div>
          </div>
        </div>

        <!-- Notre Équipe -->
        <div class="mb-16">
          <div class="text-center mb-12">
            <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">
              Notre Équipe
            </h2>
            <p class="text-xl text-gray-600 max-w-3xl mx-auto">
              Des professionnels expérimentés et passionnés à votre service
            </p>
          </div>

          <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-8 text-center">
              <div class="w-24 h-24 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
                <span class="text-white font-bold text-2xl">MC</span>
              </div>
              <h3 class="text-xl font-bold text-gray-900 mb-2">Marie-Claire Dubois</h3>
              <p class="text-emerald-600 font-medium mb-4">Fondatrice & Thérapeute</p>
              <p class="text-gray-600 text-sm">
                Psychologue clinicienne et praticienne en méditation de pleine conscience. 
                15 ans d'expérience dans l'accompagnement thérapeutique.
              </p>
            </div>

            <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-8 text-center">
              <div class="w-24 h-24 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
                <span class="text-white font-bold text-2xl">JL</span>
              </div>
              <h3 class="text-xl font-bold text-gray-900 mb-2">Jean-Luc Martin</h3>
              <p class="text-emerald-600 font-medium mb-4">Coach de Vie</p>
              <p class="text-gray-600 text-sm">
                Coach certifié en développement personnel et gestion du stress. 
                Spécialisé dans l'accompagnement des transitions de vie.
              </p>
            </div>

            <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-8 text-center">
              <div class="w-24 h-24 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
                <span class="text-white font-bold text-2xl">SB</span>
              </div>
              <h3 class="text-xl font-bold text-gray-900 mb-2">Sophie Bertrand</h3>
              <p class="text-emerald-600 font-medium mb-4">Art-Thérapeute</p>
              <p class="text-gray-600 text-sm">
                Diplômée en art-thérapie et expression créative. 
                Accompagne l'expression des émotions par l'art et la créativité.
              </p>
            </div>
          </div>
        </div>

        <!-- Nos Valeurs -->
        <div class="bg-emerald-600 rounded-3xl p-8 lg:p-12 text-white">
          <div class="text-center mb-12">
            <h2 class="text-3xl lg:text-4xl font-bold mb-4">
              Nos Engagements
            </h2>
            <p class="text-xl text-emerald-100 max-w-3xl mx-auto">
              Ce qui guide notre action au quotidien
            </p>
          </div>

          <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <div class="space-y-4">
              <div class="flex items-start space-x-3">
                <CheckCircleIcon class="h-6 w-6 text-emerald-200 mt-0.5 flex-shrink-0" />
                <div>
                  <h4 class="font-semibold mb-2">Confidentialité absolue</h4>
                  <p class="text-emerald-100">Vos échanges restent strictement confidentiels</p>
                </div>
              </div>
              <div class="flex items-start space-x-3">
                <CheckCircleIcon class="h-6 w-6 text-emerald-200 mt-0.5 flex-shrink-0" />
                <div>
                  <h4 class="font-semibold mb-2">Respect du rythme de chacun</h4>
                  <p class="text-emerald-100">Aucune pression, vous avancez à votre rythme</p>
                </div>
              </div>
              <div class="flex items-start space-x-3">
                <CheckCircleIcon class="h-6 w-6 text-emerald-200 mt-0.5 flex-shrink-0" />
                <div>
                  <h4 class="font-semibold mb-2">Formation continue</h4>
                  <p class="text-emerald-100">Notre équipe se forme régulièrement aux nouvelles approches</p>
                </div>
              </div>
            </div>
            <div class="space-y-4">
              <div class="flex items-start space-x-3">
                <CheckCircleIcon class="h-6 w-6 text-emerald-200 mt-0.5 flex-shrink-0" />
                <div>
                  <h4 class="font-semibold mb-2">Approche éco-responsable</h4>
                  <p class="text-emerald-100">Produits locaux, énergies renouvelables, démarche durable</p>
                </div>
              </div>
              <div class="flex items-start space-x-3">
                <CheckCircleIcon class="h-6 w-6 text-emerald-200 mt-0.5 flex-shrink-0" />
                <div>
                  <h4 class="font-semibold mb-2">Suivi personnalisé</h4>
                  <p class="text-emerald-100">Accompagnement avant, pendant et après votre séjour</p>
                </div>
              </div>
              <div class="flex items-start space-x-3">
                <CheckCircleIcon class="h-6 w-6 text-emerald-200 mt-0.5 flex-shrink-0" />
                <div>
                  <h4 class="font-semibold mb-2">Accessibilité</h4>
                  <p class="text-emerald-100">Tarifs adaptés et facilités de paiement disponibles</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section class="bg-gray-50 section-padding">
      <div class="container-custom text-center">
        <div class="max-w-3xl mx-auto space-y-8">
          <h2 class="text-3xl lg:text-4xl font-bold text-gray-900">
            Prêt à nous rencontrer ?
          </h2>
          <p class="text-xl text-gray-600">
            Contactez-nous pour un premier échange et découvrir comment nous pouvons vous accompagner
          </p>
          <div class="flex flex-col sm:flex-row gap-4 justify-center">
            <NuxtLink to="/contact" class="btn-primary">
              Nous contacter
            </NuxtLink>
            <a href="tel:+33123456789" class="btn-secondary">
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
  HeartIcon, 
  UserIcon, 
  SparklesIcon, 
  CheckCircleIcon 
} from '@heroicons/vue/24/outline'

useHead({
  title: 'À Propos - Parenthèse Enchantée',
  meta: [
    { name: 'description', content: 'Découvrez l\'histoire, la philosophie et l\'équipe de Parenthèse Enchantée. Notre approche bienveillante du bien-être depuis 2018.' }
  ]
})
</script>