<template>
  <div class="fondo">
    <NavBar />
    <Convertidor />
  </div>
</template>

<script>
import NavBar from "./components/NavBar";
import Convertidor from "./components/Convertidor";

export default {
  name: "App",
  components: {
    NavBar,
    Convertidor,
  },
};
</script>

<style>
.fondo {
  background-image: url('./assets/fondo1.jpg');
  height: 100vh;
  background-size: cover;
  background-position: center;
}
</style>
