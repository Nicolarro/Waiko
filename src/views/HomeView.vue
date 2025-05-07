<template>
  <div class="home">
    <AppHeader />
    <div class="hero-section">
      <!-- Contenido de la Hero -->
    </div>
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from '@/components/AppHeader.vue'; // Cambié el nombre del componente
import AppFooter from '@/components/AppFooter.vue'; // Cambié el nombre del componente

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
