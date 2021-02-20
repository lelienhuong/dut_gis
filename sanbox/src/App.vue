<template>
  <div id="app" style="position: relative">
    <Navbar />
    <Helloworld />
  </div>
</template>

<script>
import Navbar from "../../src/components/home/components/Navbar.vue";
import Helloworld from "./components/HelloWorld.vue";
export default {
  name: "App",
  components: {
    Helloworld,
    Navbar,
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
  margin-top: 60px;
}
</style>
