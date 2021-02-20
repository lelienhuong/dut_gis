<template>
  <div id="app" style="position: relative">
    <Navbar />
    <Concac />
  </div>
</template>

<script>
// import Navbar from "../../src/components/home/components/Navbar.vue";
import Navbar from "./components/navbar.vue";

import Concac from "./components/concac.vue";
export default {
  name: "App",
  components: {
    Navbar,
    Concac,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
