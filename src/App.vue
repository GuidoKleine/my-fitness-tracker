<template>
  <div id="app">
    <navBar />
    <dashboard />
    <footNote />
  </div>
</template>

<script>
import navBar from "./components/navigation";
import dashboard from "./components/Dashboard";
import footNote from "./components/footNote";

export default {
  name: "App",
  components: {
    navBar,
    dashboard,
    footNote
  }
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
