<template>
  <div id="app">
    <A msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import A from "./components/A.vue";

export default {
  name: "App",
  components: {
    A,
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
