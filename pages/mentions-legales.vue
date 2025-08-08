<template>
  <div>
    <!-- Hero Section -->
    <section class="bg-gradient-to-br from-emerald-50 to-teal-50 section-padding">
      <div class="container-custom">
        <div class="text-center">
          <h1 class="text-4xl lg:text-5xl font-bold text-gray-900 mb-6">
            Mentions Légales
          </h1>
          <p class="text-xl text-gray-600 max-w-3xl mx-auto">
            Informations légales et conditions d'utilisation
          </p>
        </div>
      </div>
    </section>

    <!-- Content -->
    <section class="bg-white section-padding">
      <div class="container-custom">
        <div class="max-w-4xl mx-auto prose prose-lg">
          <h2>Éditeur du site</h2>
          <p>
            <strong>Parenthèse Enchantée</strong><br>
            Société par Actions Simplifiée au capital de 10 000 €<br>
            Siège social : 123 Chemin de la Sérénité, 75000 Paris, France<br>
            RCS Paris : 123 456 789<br>
            SIRET : 123 456 789 00012<br>
            TVA intracommunautaire : FR12 123456789
          </p>

          <p>
            <strong>Directeur de la publication :</strong> Marie-Claire Dubois<br>
            <strong>Contact :</strong> contact@parenthese-enchantee.com<br>
            <strong>Téléphone :</strong> +33 1 23 45 67 89
          </p>

          <h2>Hébergement</h2>
          <p>
            Ce site est hébergé par :<br>
            <strong>OVH SAS</strong><br>
            2 rue Kellermann<br>
            59100 Roubaix, France<br>
            Téléphone : +33 8 99 70 17 61
          </p>

          <h2>Propriété intellectuelle</h2>
          <p>
            L'ensemble de ce site relève de la législation française et internationale sur le droit d'auteur et la propriété intellectuelle. 
            Tous les droits de reproduction sont réservés, y compris pour les documents téléchargeables et les représentations iconographiques et photographiques.
          </p>

          <h2>Protection des données personnelles</h2>
          <p>
            Conformément à la loi « Informatique et Libertés » du 6 janvier 1978 modifiée et au Règlement Général sur la Protection des Données (RGPD), 
            vous disposez d'un droit d'accès, de rectification, de suppression et d'opposition aux données personnelles vous concernant.
          </p>
          <p>
            Pour exercer ces droits, vous pouvez nous contacter à l'adresse : contact@parenthese-enchantee.com
          </p>

          <h2>Cookies</h2>
          <p>
            Ce site utilise des cookies techniques nécessaires à son bon fonctionnement. 
            Aucun cookie de tracking ou publicitaire n'est utilisé sans votre consentement explicite.
          </p>

          <h2>Responsabilité</h2>
          <p>
            Les informations contenues sur ce site sont aussi précises que possible et le site est périodiquement remis à jour, 
            mais peut toutefois contenir des inexactitudes, des omissions ou des lacunes.
          </p>

          <h2>Droit applicable</h2>
          <p>
            Tant le présent site que les modalités et conditions de son utilisation sont régis par le droit français, 
            quel que soit le lieu d'utilisation. En cas de contestation éventuelle, et après l'échec de toute tentative de 
            recherche d'une solution amiable, les tribunaux français seront seuls compétents pour connaître de ce litige.
          </p>

          <p class="text-sm text-gray-500 mt-12">
            Dernière mise à jour : Décembre 2024
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
useHead({
  title: 'Mentions Légales - Parenthèse Enchantée',
  meta: [
    { name: 'description', content: 'Mentions légales et informations juridiques de Parenthèse Enchantée.' }
  ]
})
</script>

<style scoped>
.prose h2 {
  @apply text-2xl font-bold text-gray-900 mt-8 mb-4;
}

.prose p {
  @apply text-gray-600 mb-4 leading-relaxed;
}
</style>