<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <picture>
      <source class="img" srcset="./assets/logo.webp" type="image/webp">
      <img src="./assets/logo.png" alt="Screenshot">
    </picture>

    <div class="demo"> 

    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
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
.demo {
  width: 30px;
  height: 30px;
  background: url('./assets/logo.png');
}
.img {
  width: 200px;
  height: 200px;
}
</style>