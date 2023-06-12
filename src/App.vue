<script setup>
import headerComponent from './components/headerComponent.vue';
import navbarComponent from './components/navbarComponent.vue';
import footerComponent from './components/footerComponent.vue';

import HomeView from './views/HomeView.vue';
</script>

<template>
  <main>
    <headerComponent />
    <navbarComponent />
    <HomeView />
    <footerComponent /> 
  </main>
</template>



<style scoped>

</style>
