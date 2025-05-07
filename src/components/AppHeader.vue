<template>
  <header class="header">
    <nav>
      <router-link to="/">Inicio</router-link>
      <router-link to="/quien-somos">Quiénes somos</router-link>
      <router-link to="/servicios">Servicios</router-link>
      <router-link to="/contacto">Contacto</router-link>
    </nav>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style scoped>
.header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background-color: #144553;
  color: #fff;
  padding: 10px;
  z-index: 10;
}

nav {
  display: flex;
  justify-content: space-around;
}

a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

a:hover {
  color: #D1F994;
}
</style>
