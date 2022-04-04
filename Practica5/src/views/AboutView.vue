<template>
  <div class="Pastelero">
    <h1>Datos del pastelero</h1>
    <br>
    <cantidadSabores/>
    <br>
    <cantidadAdornos/>
    <br>
    <pedidosRealizados/>
  </div>
</template>

<script>
import cantidadSabores from "../components/cantidadSabores.vue"
import cantidadAdornos from "../components/cantidadAdornos.vue"
import pedidosRealizados from "../components/pedidosRealizados.vue"

export default {
  name: 'AboutView',
  components:{
    cantidadSabores,
    cantidadAdornos,
    pedidosRealizados,
  }
}
</script>


<style>
  table,th,td{
    border: 1px solid black;
    border-collapse: collapse;
  }
</style>