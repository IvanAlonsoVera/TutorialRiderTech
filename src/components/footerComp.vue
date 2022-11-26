<template>
  <footer class="row bg-secondary text-white text-center mt-5" v-html="footer">
  </footer>
</template>
<script>
  export default {
    name: 'footerComp',
    data() {
      return {
        footer: "<p>Preguntas Frecuentes<br/>Cookies <br/>Aviso legal<br />Información Legal ConnectedDrive <br/>Política de Privacidad <br/>Condiciones de Uso en RR.SS < br />Política de Privacidad RR.SS <br/>© BMW ES 2022</p>",
      }
    }
  }
</script>
