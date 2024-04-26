<script setup lang="ts">
import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';
</script>

<template>
  <header>
    <the-header></the-header>
  </header>

  <main>
<h1> Tous les produits {{ nbr_cards }}</h1>
  </main>
  <footer>
   <the-footer></the-footer>
  </footer>
</template>

<style scoped>

</style>
