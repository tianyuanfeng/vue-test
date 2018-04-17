<template>
  <div id="app">
    <img src="./assets/banner005.jpg" class="topImage">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Home msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Home from './components/Home.vue'

export default {
  name: 'app',
  components: {
    HelloWorld, Home
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /*margin-top: 60px;*/
}
.topImage {
  width: 100%;
}
</style>
