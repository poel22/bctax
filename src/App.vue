<template>
  <div id="app">
    <MenuBar />
    <Overview />
  </div>
</template>

<script>
import MenuBar from "./components/MenuBar.vue";
import Overview from "./components/Overview.vue";

export default {
  name: "App",
  components: {
    MenuBar,
    Overview
  },
  mounted() {
    console.log("mounted App");
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
