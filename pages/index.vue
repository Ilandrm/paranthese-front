<template>
  <div>
    <!-- Hero Section -->
    <section class="relative bg-gradient-to-br from-emerald-50 to-teal-50 overflow-hidden">
      <div class="absolute inset-0 bg-white/20"></div>
      <div class="relative container-custom section-padding">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
          <div class="space-y-8">
            <div class="space-y-4">
              <h1 class="text-4xl lg:text-6xl font-bold text-gray-900 leading-tight">
                Faites <span class="text-emerald-600">des Parenthèses</span><br>
                dans votre vie
              </h1>
              <p class="text-xl text-gray-600 leading-relaxed">
                Que çe soit par un sejour, un atelirer, des journées bien être ou un travail personnel, offrez vous ces temps de pause pour avancer ou vous ressourçer

              </p>
            </div>
            <div class="flex flex-col sm:flex-row gap-4">
              <NuxtLink to="/seminaires" class="btn-primary text-center">
                Découvrir nos séminaires
              </NuxtLink>
              <NuxtLink to="/contact" class="btn-secondary text-center">
                Nous contacter
              </NuxtLink>
            </div>
          </div>
          <div class="relative">
            <div class="aspect-square bg-gradient-to-br from-emerald-200 to-teal-300 rounded-3xl shadow-2xl flex items-center justify-center">
              <div class="text-center text-white">
                <div class="w-24 h-24 bg-white/20 rounded-full flex items-center justify-center mx-auto mb-4">
                  <HeartIcon class="h-12 w-12" />
                </div>
                <p class="text-lg font-medium">Sérénité & Bien-être</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Services Section -->
    <section class="bg-white section-padding">
      <div class="container-custom">
        <div class="text-center mb-16">
          <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">
            Pour vous (re)trouver
          </h2>
          <p class="text-xl text-gray-600 max-w-3xl mx-auto">
            et si vous preniez un moment rien que pour vous ? faites des pauses et apprenez à vous ecouter
          </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-8 text-center hover:shadow-lg transition-shadow">
            <div class="w-16 h-16 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
              <UserGroupIcon class="h-8 w-8 text-white" />
            </div>
            <h3 class="text-xl font-bold text-gray-900 mb-4">"La parenthèse enchanté"</h3>
            <p class="text-gray-600 mb-6">
            Des sejours bien etre pour vous ressourcer, vous transformer, vous retrouver... dans des lieux hors du temps entre yoga, méditation, soins, nature et echanges
              </p>
            <NuxtLink to="/seminaires" class="text-emerald-600 font-medium hover:text-emerald-700">
              En savoir plus →
            </NuxtLink>
          </div>

          <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-8 text-center hover:shadow-lg transition-shadow">
            <div class="w-16 h-16 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
              <UserIcon class="h-8 w-8 text-white" />
            </div>
            <h3 class="text-xl font-bold text-gray-900 mb-4">Nos journées mystères</h3>
            <p class="text-gray-600 mb-6">
              Lachez prise et venez vivre une journée bien être
            </p>
            <NuxtLink to="/seminaires" class="text-emerald-600 font-medium hover:text-emerald-700">
              En savoir plus →
            </NuxtLink>
          </div>

          <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-8 text-center hover:shadow-lg transition-shadow">
            <div class="w-16 h-16 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
              <HomeIcon class="h-8 w-8 text-white" />
            </div>
            <h3 class="text-xl font-bold text-gray-900 mb-4">Nos ateliers</h3>
            <p class="text-gray-600 mb-6">
            </p>
            <NuxtLink to="/hebergement" class="text-emerald-600 font-medium hover:text-emerald-700">
              En savoir plus →
            </NuxtLink>
          </div>
          <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-8 text-center hover:shadow-lg transition-shadow">
            <div class="w-16 h-16 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
              <HomeIcon class="h-8 w-8 text-white" />
            </div>
            <h3 class="text-xl font-bold text-gray-900 mb-4">Pour aller plus loin</h3>
            <p class="text-gray-600 mb-6">
              vidéos et exercices à suivre à votre rythme... pour avancer sur votre chemin interieur
            </p>
            <NuxtLink to="/hebergement" class="text-emerald-600 font-medium hover:text-emerald-700">
              En savoir plus →
            </NuxtLink>
          </div>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section class="bg-gray-50 section-padding">
      <div class="container-custom">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
          <div class="space-y-6">
            <h2 class="text-3xl lg:text-4xl font-bold text-gray-900">
              Un lieu d'exception pour votre bien-être
            </h2>
            <p class="text-lg text-gray-600 leading-relaxed">
              Notre centre vous accueille dans un environnement calme et serein, 
              spécialement conçu pour favoriser la détente et la reconnexion avec soi-même.
            </p>
            <div class="space-y-4">
              <div class="flex items-start space-x-3">
                <CheckCircleIcon class="h-6 w-6 text-emerald-600 mt-0.5" />
                <div>
                  <h4 class="font-semibold text-gray-900">Cadre naturel exceptionnel</h4>
                  <p class="text-gray-600">Entouré de verdure et de tranquillité</p>
                </div>
              </div>
              <div class="flex items-start space-x-3">
                <CheckCircleIcon class="h-6 w-6 text-emerald-600 mt-0.5" />
                <div>
                  <h4 class="font-semibold text-gray-900">Accompagnement professionnel</h4>
                  <p class="text-gray-600">Équipe expérimentée et bienveillante</p>
                </div>
              </div>
              <div class="flex items-start space-x-3">
                <CheckCircleIcon class="h-6 w-6 text-emerald-600 mt-0.5" />
                <div>
                  <h4 class="font-semibold text-gray-900">Approche personnalisée</h4>
                  <p class="text-gray-600">Programmes adaptés à vos besoins</p>
                </div>
              </div>
            </div>
            <NuxtLink to="/a-propos" class="btn-primary inline-block">
              Découvrir notre approche
            </NuxtLink>
          </div>
          <div class="relative">
            <div class="aspect-[4/3] bg-gradient-to-br from-emerald-200 to-teal-300 rounded-3xl shadow-2xl flex items-center justify-center">
              <div class="text-center text-white">
                <div class="w-24 h-24 bg-white/20 rounded-full flex items-center justify-center mx-auto mb-4">
                  <SparklesIcon class="h-12 w-12" />
                </div>
                <p class="text-lg font-medium">Votre transformation commence ici</p>
              </div>
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
            Prêt à vivre votre parenthèse bien-être ?
          </h2>
          <p class="text-xl text-emerald-100">
            Contactez-nous dès aujourd'hui pour réserver votre séjour ou obtenir plus d'informations
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
  HeartIcon, 
  UserGroupIcon, 
  UserIcon, 
  HomeIcon, 
  CheckCircleIcon, 
  SparklesIcon 
} from '@heroicons/vue/24/outline'

useHead({
  title: 'Accueil - Parenthèse Enchantée',
  meta: [
    { name: 'description', content: 'Venez vivre l\'expérience d\'un séjour bien-être dans un endroit doux, calme et serein. Séminaires et hébergement pour votre ressourcement.' }
  ]
})
</script>