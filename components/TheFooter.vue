<template>
  <footer class="bg-gray-900 text-white">
    <div class="container-custom py-16">
      <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
        <!-- Logo et description -->
        <div class="md:col-span-2">
          <div class="flex items-center space-x-3 mb-4">
            <div class="w-10 h-10 bg-emerald-600 rounded-full flex items-center justify-center">
              <span class="text-white font-bold text-lg">PE</span>
            </div>
            <div>
              <h3 class="text-xl font-bold">Parenthèse Enchantée</h3>
              <p class="text-emerald-400">Séminaires Bien-être</p>
            </div>
          </div>
          <p class="text-gray-300 mb-6 max-w-md">
            Venez vivre l'expérience d'un séjour bien-être dans un endroit doux, calme et serein. 
            Offrez-vous ce moment pour vous et repartez ressourcés.
          </p>
          <div class="flex space-x-4">
            <a href="#" class="text-gray-400 hover:text-emerald-400 transition-colors">
              <span class="sr-only">Facebook</span>
              <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                <path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/>
              </svg>
            </a>
            <a href="#" class="text-gray-400 hover:text-emerald-400 transition-colors">
              <span class="sr-only">Instagram</span>
              <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                <path d="M12.017 0C5.396 0 .029 5.367.029 11.987c0 6.62 5.367 11.987 11.988 11.987c6.62 0 11.987-5.367 11.987-11.987C24.014 5.367 18.637.001 12.017.001zM8.449 16.988c-1.297 0-2.448-.49-3.323-1.297L3.182 17.635l1.935-1.935c.807.807 1.958 1.297 3.323 1.297c2.58 0 4.677-2.097 4.677-4.677s-2.097-4.677-4.677-4.677c-1.365 0-2.516.49-3.323 1.297L3.182 6.365l1.944-1.944c.875-.807 2.026-1.297 3.323-1.297c2.58 0 4.677 2.097 4.677 4.677s-2.097 4.677-4.677 4.677z"/>
              </svg>
            </a>
          </div>
        </div>

        <!-- Navigation rapide -->
        <div>
          <h4 class="text-lg font-semibold mb-4">Navigation</h4>
          <ul class="space-y-2">
            <li><NuxtLink to="/" class="text-gray-300 hover:text-emerald-400 transition-colors">Accueil</NuxtLink></li>
            <li><NuxtLink to="/seminaires" class="text-gray-300 hover:text-emerald-400 transition-colors">Séminaires</NuxtLink></li>
            <li><NuxtLink to="/hebergement" class="text-gray-300 hover:text-emerald-400 transition-colors">Hébergement</NuxtLink></li>
            <li><NuxtLink to="/a-propos" class="text-gray-300 hover:text-emerald-400 transition-colors">À propos</NuxtLink></li>
            <li><NuxtLink to="/contact" class="text-gray-300 hover:text-emerald-400 transition-colors">Contact</NuxtLink></li>
          </ul>
        </div>

        <!-- Contact -->
        <div>
          <h4 class="text-lg font-semibold mb-4">Contact</h4>
          <div class="space-y-2 text-gray-300">
            <p class="flex items-center">
              <PhoneIcon class="h-5 w-5 mr-2 text-emerald-400" />
              +33 1 23 45 67 89
            </p>
            <p class="flex items-center">
              <EnvelopeIcon class="h-5 w-5 mr-2 text-emerald-400" />
              contact@parenthese-enchantee.com
            </p>
            <p class="flex items-start">
              <MapPinIcon class="h-5 w-5 mr-2 text-emerald-400 mt-0.5" />
              123 Chemin de la Sérénité<br>
              75000 Paris, France
            </p>
          </div>
        </div>
      </div>

      <div class="border-t border-gray-800 mt-12 pt-8 text-center text-gray-400">
        <p>&copy; 2024 Parenthèse Enchantée. Tous droits réservés.</p>
      </div>
    </div>
  </footer>
</template>

<script setup>
import { PhoneIcon, EnvelopeIcon, MapPinIcon } from '@heroicons/vue/24/outline'
</script>