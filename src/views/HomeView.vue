<template>
  <div class="home hero-section">
    <div class="hero-section">
      <h1 v-scroll-reveal="{ delay: 200 }">WAIKO Gestión Ambiental Integral</h1>
      <h2 v-scroll-reveal="{ delay: 400 }">
        Facilitamos el cumplimiento normativo ambiental para empresas, comercios
        y grandes obras.
      </h2>
      <q-btn
        v-scroll-reveal="{ delay: 600 }"
        name="Asesoramiento"
        unelevated
        color="brown-5"
        label="Solicitar asesoramiento inmediato"
        :size="'lg'"
        class="boton-destacado q-px-xl q-py-md"
      ></q-btn>
    </div>
    <div class="info-section">
      <h3>
        Con más de 12 años de experiencia, acompañamos a nuestros clientes en la
        gestión ambiental diaria y en el control de obras financiadas por
        organismos internacionales.
      </h3>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomePage", // Cambio de nombre
  components: {},
};
</script>

<style scoped>
.home {
  margin-top: 100px; /* Espacio para el header fijo */
  display: flex;
  flex-direction: column;
  margin-top: 100px; /* Mantener el espacio para el header fijo */
}
.hero-section {
  height: 120vh;
  background: linear-gradient(rgba(44, 62, 80, 0.7), rgba(44, 62, 80, 0.7)),
    url("../assets/BackgroundHome.jpg") no-repeat center center/cover;
}

/* AGREGAR */
.info-section {
  padding: 3rem 1rem;
  background-color: #f8f9fa;
}
.hero-section h1 {
  font-size: 3.5rem;
  color: #fff;
  text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
}

h2 {
  font-size: 1.8rem !important;
  color: #fff;
  line-height: 1.4;
  text-shadow: 0 1px 3px rgba(0, 0, 0, 0.2);
}

h3 {
  font-size: 1.5rem !important;
  text-align: center;
  color: #2c3e50;
  max-width: 800px;
  margin: 0 auto;
}

.mainSection {
  background-color: #f8f9fa;
}
button.home {
  background-color: #75634f;
  color: #fff;
  border: none;
  font-size: 1.5rem;
  cursor: pointer;
  border-radius: 60%;
  margin-top: 20px;
}
.boton {
  margin: 10px;
}
.boton-destacado {
  font-weight: bold;
  letter-spacing: 0.5px;
  border-radius: 8px;
  transition: transform 0.3s, box-shadow 0.3s;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

.boton-destacado:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}
</style>
