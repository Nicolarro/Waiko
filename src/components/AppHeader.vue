<template>
  <header class="header">
    <div class="container">
      <img src="../assets/5(3).png" class="imagenLogo" alt="Logo" />
      <nav>
        <router-link to="/">Inicio</router-link>
        <router-link to="/quien-somos">Quiénes somos</router-link>
        <router-link to="/servicios">Servicios</router-link>
        <router-link to="/contacto">Contacto</router-link>
      </nav>
    </div>
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
  background-color: #75634f;
  color: #fff;
  padding: 10px;
  z-index: 10;
}

.container {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  margin: 0 auto;
}
nav {
  display: flex;
  justify-content: space-around !important;
}

a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  padding: 0px 50px 0px 0px;
}

a:hover {
  color: #d1f994;
}
.imagenLogo {
  height: 80px;
}
</style>
