<template>
  <div class="home">
    <AppHeader />

    <AppFooter />
  </div>
</template>

<script>
import AppHeader from '@/components/AppHeader.vue';
import AppFooter from '@/components/AppFooter.vue';

export default {
  name: 'HomePage', // Cambio de nombre
  components: {
    AppHeader,
    AppFooter
  }
};
</script>

<style scoped>
.home {
  margin-top: 100px; /* Espacio para el header fijo */
}
.hero-section {
  height: 100vh; /* Pantalla completa */
  /* background: url('../assets/hero-image.jpg') no-repeat center center/cover; */
}
</style>
