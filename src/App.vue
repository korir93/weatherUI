<template>
  <div id="app">
    <div class="text">
      <img alt="Vue logo" src="./assets/logo.png">
      <h2>PowerGen Weather Project</h2>
    </div>
    <weather/>
  </div>
</template>

<script>
import weather from "./components/weather.vue";
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "app",
  components: {
    weather
  }
};
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
img {
  height: 100px;
}
.text{
  margin-bottom: 30px;
}
</style>
