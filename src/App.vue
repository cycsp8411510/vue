<template>
  <v-app id="app">
    <router-view />
  </v-app>
</template>

<script>
import Test2 from "./components/test2";
export default {
  name: "App",
  components: {Test2},
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Poppins");
#app {
  font-family: "Poppins";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  text-transform: unset !important;
}

body {
  min-width: 320px;
}
</style>
