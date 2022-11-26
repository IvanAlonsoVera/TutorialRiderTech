<template>
  <div class="row text-white text-center mb-5">
    <nav class="navbar navbar-expand-sm bg-secondary text-center">
      <div class="container-fluid">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="p-4 nav-link active" href="#"><img width="50px" src="../img/bmwlogo.png" /></a>
          </li>
          <li v-for="item in items" class="p-4 nav-item">
            <a class="nav-link text-white active" href="#">{{item}}</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>
<script>
  export default {
    name: 'navBar',
    data() {
      return {
        items: ["Modelos", "buscar y comprar", "Movilidad Electrica", "Propietarios", "Mundo BMW"]
      }
    }
  }
</script>
