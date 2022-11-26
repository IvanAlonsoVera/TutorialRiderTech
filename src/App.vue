<template>
  <div id="app">
    <navBar></navBar>
    <div class="row">
      <imgComp></imgComp>
      <infoComp></infoComp>
    </div>
    <footerComp></footerComp>
  </div>
</template>

<script>
  import navBar from './components/navBar'
  import imgComp from './components/imgComp'
  import infoComp from './components/infoComp'
  import footerComp from './components/footerComp'
  export default {
    name: 'app',
    components: { navBar, imgComp, infoComp, footerComp },
  }
</script>
<style>
  body {
    background-image: url("./img/bg.jpg");
    background-repeat: no-repeat;
    background-position-x: center;
    background-position-y: center;
    background-size: cover;
  }

  nav {
    opacity: 75%;
  }

  footer {
    opacity: 75%;
  }
</style>

