<template>
  <div id="app">
    <Training />
  </div>
</template>

<script>
import Training from "./components/Training.vue";

export default {
  name: "App",
  components: {
    Training,
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
