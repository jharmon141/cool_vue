<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view></router-view>
  </div>
</template>

<script>
import store from './store/index.js'

export default {
  name: 'app'
}
</script>

<style>

html {
    position: relative;
    min-height: 100%;
}

body {
    margin: 0 0 100px; /* bottom = footer height */
}

footer {
    position: absolute;
    left: 0;
    bottom: 0;
    height: 100px;
    width: 100%;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
