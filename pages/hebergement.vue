<template>
  <div>
    <!-- Hero Section -->
    <section class="bg-gradient-to-br from-emerald-50 to-teal-50 section-padding">
      <div class="container-custom">
        <div class="text-center mb-16">
          <h1 class="text-4xl lg:text-5xl font-bold text-gray-900 mb-6">
            Hébergement & Cadre de Vie
          </h1>
          <p class="text-xl text-gray-600 max-w-3xl mx-auto">
            Un lieu d'exception pensé pour votre confort et votre sérénité
          </p>
        </div>
      </div>
    </section>

    <!-- Accommodation Types -->
    <section class="bg-white section-padding">
      <div class="container-custom">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 mb-16">
          <!-- Chambres individuelles -->
          <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-3xl p-8 lg:p-12">
            <div class="space-y-6">
              <div class="w-16 h-16 bg-emerald-600 rounded-full flex items-center justify-center">
                <HomeIcon class="h-8 w-8 text-white" />
              </div>
              <div>
                <h2 class="text-2xl lg:text-3xl font-bold text-gray-900 mb-4">
                  Chambres Individuelles
                </h2>
                <p class="text-gray-600 text-lg leading-relaxed mb-6">
                  Profitez d'un espace privé et confortable, spécialement aménagé pour favoriser 
                  la détente et la réflexion personnelle.
                </p>
                <div class="space-y-3 mb-8">
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-emerald-600" />
                    <span class="text-gray-700">Salle de bain privative</span>
                  </div>
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-emerald-600" />
                    <span class="text-gray-700">Vue sur le jardin</span>
                  </div>
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-emerald-600" />
                    <span class="text-gray-700">Coin lecture et méditation</span>
                  </div>
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-emerald-600" />
                    <span class="text-gray-700">Linge de maison fourni</span>
                  </div>
                </div>
                <div class="bg-white rounded-xl p-6">
                  <div class="flex justify-between items-center">
                    <span class="text-gray-600">À partir de</span>
                    <span class="text-2xl font-bold text-emerald-600">85€/nuit</span>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Chambres partagées -->
          <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-3xl p-8 lg:p-12">
            <div class="space-y-6">
              <div class="w-16 h-16 bg-blue-600 rounded-full flex items-center justify-center">
                <UserGroupIcon class="h-8 w-8 text-white" />
              </div>
              <div>
                <h2 class="text-2xl lg:text-3xl font-bold text-gray-900 mb-4">
                  Chambres Partagées
                </h2>
                <p class="text-gray-600 text-lg leading-relaxed mb-6">
                  Partagez votre expérience avec d'autres participants dans un esprit de convivialité 
                  et d'échange, tout en conservant votre intimité.
                </p>
                <div class="space-y-3 mb-8">
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-blue-600" />
                    <span class="text-gray-700">2 lits individuels par chambre</span>
                  </div>
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-blue-600" />
                    <span class="text-gray-700">Salle de bain partagée</span>
                  </div>
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-blue-600" />
                    <span class="text-gray-700">Espace de rangement personnel</span>
                  </div>
                  <div class="flex items-center space-x-3">
                    <CheckCircleIcon class="h-5 w-5 text-blue-600" />
                    <span class="text-gray-700">Ambiance chaleureuse</span>
                  </div>
                </div>
                <div class="bg-white rounded-xl p-6">
                  <div class="flex justify-between items-center">
                    <span class="text-gray-600">À partir de</span>
                    <span class="text-2xl font-bold text-blue-600">55€/nuit</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Espaces communs -->
        <div class="bg-gray-50 rounded-3xl p-8 lg:p-12">
          <div class="text-center mb-12">
            <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">
              Espaces Communs
            </h2>
            <p class="text-xl text-gray-600 max-w-3xl mx-auto">
              Des lieux de vie pensés pour favoriser la détente, les échanges et la reconnexion
            </p>
          </div>

          <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
            <div class="text-center">
              <div class="w-20 h-20 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
                <BuildingLibraryIcon class="h-10 w-10 text-white" />
              </div>
              <h3 class="text-xl font-bold text-gray-900 mb-4">Salle de Méditation</h3>
              <p class="text-gray-600">
                Un espace silencieux et apaisant, dédié à la méditation et à la réflexion personnelle.
              </p>
            </div>

            <div class="text-center">
              <div class="w-20 h-20 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
                <HomeModernIcon class="h-10 w-10 text-white" />
              </div>
              <h3 class="text-xl font-bold text-gray-900 mb-4">Salon Détente</h3>
              <p class="text-gray-600">
                Un lieu convivial pour se retrouver, échanger et partager des moments de convivialité.
              </p>
            </div>

            <div class="text-center">
              <div class="w-20 h-20 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
                <SparklesIcon class="h-10 w-10 text-white" />
              </div>
              <h3 class="text-xl font-bold text-gray-900 mb-4">Jardin Zen</h3>
              <p class="text-gray-600">
                Un jardin paysager avec espaces de contemplation, fontaine et coins lecture extérieurs.
              </p>
            </div>

            <div class="text-center">
              <div class="w-20 h-20 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6">
                <CakeIcon class="h-10 w-10 text-white" />
              </div>
              <h3 class="text-xl font-bold text-gray-900 mb-4">Espace Restauration</h3>
              <p class="text-gray-600">
                Cuisine équipée et salle à manger pour des repas sains préparés avec des produits locaux.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Services inclus -->
    <section class="bg-white section-padding">
      <div class="container-custom">
        <div class="text-center mb-16">
          <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">
            Services Inclus
          </h2>
          <p class="text-xl text-gray-600 max-w-3xl mx-auto">
            Tout est pensé pour que vous puissiez vous concentrer sur l'essentiel : votre bien-être
          </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-6 text-center">
            <div class="w-12 h-12 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-4">
              <CakeIcon class="h-6 w-6 text-white" />
            </div>
            <h3 class="text-lg font-bold text-gray-900 mb-2">Repas Équilibrés</h3>
            <p class="text-gray-600 text-sm">Cuisine saine et savoureuse avec produits bio et locaux</p>
          </div>

          <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-6 text-center">
            <div class="w-12 h-12 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-4">
              <WifiIcon class="h-6 w-6 text-white" />
            </div>
            <h3 class="text-lg font-bold text-gray-900 mb-2">WiFi Gratuit</h3>
            <p class="text-gray-600 text-sm">Connexion internet dans les espaces communs</p>
          </div>

          <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-6 text-center">
            <div class="w-12 h-12 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-4">
              <TruckIcon class="h-6 w-6 text-white" />
            </div>
            <h3 class="text-lg font-bold text-gray-900 mb-2">Parking Gratuit</h3>
            <p class="text-gray-600 text-sm">Stationnement sécurisé sur place</p>
          </div>

          <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-6 text-center">
            <div class="w-12 h-12 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-4">
              <SparklesIcon class="h-6 w-6 text-white" />
            </div>
            <h3 class="text-lg font-bold text-gray-900 mb-2">Ménage Quotidien</h3>
            <p class="text-gray-600 text-sm">Entretien des chambres et espaces communs</p>
          </div>

          <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-6 text-center">
            <div class="w-12 h-12 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-4">
              <BookOpenIcon class="h-6 w-6 text-white" />
            </div>
            <h3 class="text-lg font-bold text-gray-900 mb-2">Bibliothèque</h3>
            <p class="text-gray-600 text-sm">Ouvrages sur le développement personnel et le bien-être</p>
          </div>

          <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-6 text-center">
            <div class="w-12 h-12 bg-emerald-600 rounded-full flex items-center justify-center mx-auto mb-4">
              <HeartIcon class="h-6 w-6 text-white" />
            </div>
            <h3 class="text-lg font-bold text-gray-900 mb-2">Accueil Personnalisé</h3>
            <p class="text-gray-600 text-sm">Équipe disponible et bienveillante 24h/24</p>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section class="bg-emerald-600 section-padding">
      <div class="container-custom text-center">
        <div class="max-w-3xl mx-auto space-y-8">
          <h2 class="text-3xl lg:text-4xl font-bold text-white">
            Réservez votre séjour
          </h2>
          <p class="text-xl text-emerald-100">
            Contactez-nous pour vérifier les disponibilités et réserver votre hébergement
          </p>
          <div class="flex flex-col sm:flex-row gap-4 justify-center">
            <NuxtLink to="/contact" class="bg-white text-emerald-600 hover:bg-gray-50 font-medium py-3 px-8 rounded-lg transition-colors duration-200 shadow-lg">
              Vérifier les disponibilités
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
  HomeIcon, 
  UserGroupIcon, 
  CheckCircleIcon, 
  BuildingLibraryIcon,
  HomeModernIcon,
  SparklesIcon,
  CakeIcon,
  WifiIcon,
  TruckIcon,
  BookOpenIcon,
  HeartIcon
} from '@heroicons/vue/24/outline'

useHead({
  title: 'Hébergement - Parenthèse Enchantée',
  meta: [
    { name: 'description', content: 'Découvrez nos hébergements confortables dans un cadre serein. Chambres individuelles et partagées avec tous les services inclus.' }
  ]
})
</script>