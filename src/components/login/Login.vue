<template>
  <form id="login" class="box column is-one-quarter p-5">
    <img src="../../assets/logo-platzi-music.png" />

    <h1 class="title is-5 primary-color m-2">Registro estacion platzi</h1>

    <div class="control">
      <TextInputs labelName="Nombre" />
      <TextInputs labelName="Apellido" />
      <TextInputs labelName="Cargo" />
    </div>

    <div class="control py-5 is-flex is-justify-content-flex-end">
      <Button content="ENVIAR" />
    </div>
  </form>
</template>


<script>
import TextInputs from "../login/TextInputs.vue";
import Button from "../login/Button.vue";

export default {
  name: "Login",
  components: {
    TextInputs,
    Button,
  },
};
</script>

