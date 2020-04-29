<template>
  <div id="app">
    <div id="nav">
      <layout></layout>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import layout from "@/layout/index.vue";

export default {
  name: "Home",
  components: {
    layout
  }
};
</script>

<style lang="scss">
body {
  // background-color: red;
  padding: 0;
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
