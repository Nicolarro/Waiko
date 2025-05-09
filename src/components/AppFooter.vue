<template>
  <footer class="footer">
    <p>
      Evaluación de Impacto Ambiental - Impacto Acústico - Seguridad e Higiene
      Laboral
    </p>
  </footer>
</template>

<script>
export default {
  name: "AppFooter",
};
</script>

<style scoped>
.footer {
  position: relative;
  bottom: 0;
  left: 0;
  width: 100%;
  background-color: #75634f;
  color: #fff;
  text-align: center;
  padding: 10px;
  font-size: 14px;
  line-height: 1.6;
  white-space: nowrap;
  overflow: hidden;
}

.footer p {
  margin: 0;
  padding: 0;
  display: inline-block;
  max-width: 100%;
  text-overflow: ellipsis;
  overflow: hidden;
}
</style>
