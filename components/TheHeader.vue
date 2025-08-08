<template>
  <header class="bg-white shadow-sm sticky top-0 z-50">
    <nav class="container-custom">
      <div class="flex justify-between items-center py-4">
        <!-- Logo -->
        <div class="flex items-center space-x-3">
          <div class="w-10 h-10 bg-emerald-600 rounded-full flex items-center justify-center">
            <span class="text-white font-bold text-lg">PE</span>
          </div>
          <div>
            <h1 class="text-xl font-bold text-gray-900">Parenthèse Enchantée</h1>
            <p class="text-sm text-emerald-600">Séminaires Bien-être</p>
          </div>
        </div>

        <!-- Desktop Navigation -->
        <div class="hidden md:flex items-center space-x-8">
          <NuxtLink to="/" class="text-gray-700 hover:text-emerald-600 transition-colors font-medium">
            Qui sommes nous
          </NuxtLink>
          <NuxtLink to="/seminaires" class="text-gray-700 hover:text-emerald-600 transition-colors font-medium">
            Nos séjours
          </NuxtLink>
          <NuxtLink to="/a-propos" class="text-gray-700 hover:text-emerald-600 transition-colors font-medium">
            Nos ateliers
          </NuxtLink>
          <NuxtLink to="/hebergement" class="text-gray-700 hover:text-emerald-600 transition-colors font-medium">
            Pour aller plus loin
          </NuxtLink>

          <NuxtLink to="/contact" class="btn-primary">
            Contact
          </NuxtLink>
        </div>

        <!-- Mobile menu button -->
        <button 
          @click="mobileMenuOpen = !mobileMenuOpen"
          class="md:hidden p-2 rounded-md text-gray-700 hover:text-emerald-600 hover:bg-gray-100"
        >
          <Bars3Icon v-if="!mobileMenuOpen" class="h-6 w-6" />
          <XMarkIcon v-else class="h-6 w-6" />
        </button>
      </div>

      <!-- Mobile Navigation -->
      <div v-if="mobileMenuOpen" class="md:hidden py-4 border-t border-gray-200">
        <div class="flex flex-col space-y-4">
          <NuxtLink to="/" class="text-gray-700 hover:text-emerald-600 transition-colors font-medium">
            Accueil
          </NuxtLink>
          <NuxtLink to="/seminaires" class="text-gray-700 hover:text-emerald-600 transition-colors font-medium">
            Séminaires
          </NuxtLink>
          <NuxtLink to="/hebergement" class="text-gray-700 hover:text-emerald-600 transition-colors font-medium">
            Hébergement
          </NuxtLink>
          <NuxtLink to="/a-propos" class="text-gray-700 hover:text-emerald-600 transition-colors font-medium">
            À propos
          </NuxtLink>
          <NuxtLink to="/contact" class="btn-primary inline-block text-center">
            Contact
          </NuxtLink>
        </div>
      </div>
    </nav>
  </header>
</template>

<script setup>
import { ref } from 'vue'
import { Bars3Icon, XMarkIcon } from '@heroicons/vue/24/outline'

const mobileMenuOpen = ref(false)
</script>