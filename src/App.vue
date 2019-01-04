<template>
  <div id="app">
    <FlowDiagram/>
  </div>
</template>

<script>
import FlowDiagram from "./components/FlowDiagram.vue";
export default {
  name: "app",
  components: { FlowDiagram }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
