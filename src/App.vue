<template>
  <div id="app">
    <img src="./assets/campany-logo.png">
    <div style="font-size: 2em; margin-top: -15px;">✗</div>
    <img src="./assets/logo.png" style="width: 100px;">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
