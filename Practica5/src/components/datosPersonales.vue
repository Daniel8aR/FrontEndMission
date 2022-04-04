<template>
    <div class="datosPersonales"> 
        <label for="Nombre">Danos tu nombre</label>
        <input type="text" name="Nombre" id="Nombre" placeholder="Nombre">
        <br>
        <label for="Apellidos">Danos tus apellidos</label>
        <input type="text" name="Apellidos" id="Apellidos" placeholder="Apellidos">
        <br>
        <label for="Tel">Coluque su número</label>
        <input type="tel" name="Tel" id="Tel" placeholder="Numero telefónico" maxlength="10">
        <br>
        <label for="Correo">Ingrese su correo</label><br>
        <input type="email" id="Correo" name="Correo">
        <br>
    </div>
</template>

<script>

export default {
    name: 'datosPersonales',
}
</script>