<template>
  <div id="app">
    <nav-bar></nav-bar>
    <banner></banner>
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import Banner from "./components/Banner.vue";
export default {
  name: "App",
  components: {
    NavBar,
    Banner,
  },
};
</script>

<style>
@import "../src/assets/css/style.css";
</style>
