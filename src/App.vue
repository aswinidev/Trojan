<template>
<div id="app">
  <Slider/>
  </div>
</template>

<script>
import Slider from './components/Slider.vue'
// import About from './components/About.vue'
export default {
  name: "app",
  components: {
    Slider,
    // About,
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
  /* margin-top: 60px; */
}
body {
  margin: 0px;
}
</style>
