<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <datos-pasteleria/>
    <br>
    <sabores-pasteles/>
    <br>
    <adornos-pasteleria/>
    <br>
    <form action="pedido.js">
      <datos-personales/>
      <br>
      <combinar-sabores/>
      <br>
      <combinar-adornos/>
      <br>
      <input type="reset">
      <input type="submit">
    </form>
  </div>
</template>

<script>
import datosPasteleria from "../components/datosPasteleria.vue";
import saboresPasteles from "../components/saboresPasteles.vue";
import adornosPasteleria from "../components/adornosPasteleria.vue";
import datosPersonales from "../components/datosPersonales.vue";
import combinarSabores from "../components/combinarSabores.vue";
import combinarAdornos from "../components/combinarAdornos.vue";

export default {
  name: 'HomeView',
  components:{
    datosPasteleria,
    saboresPasteles,
    adornosPasteleria,
    combinarSabores,
    datosPersonales,
    combinarAdornos,
  }
}
</script>

<style>
  *{
    font-family: Arial;
  }
  img{
    width: 500px;
  }
</style>

