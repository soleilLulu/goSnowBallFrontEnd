<template>
  <div id="app">
    <!-- <login></login> -->
    <nav-bar></nav-bar>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
// import Login from './pages/login'
import NavBar from './components/navbar.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    NavBar
  }
}
</script>

<style>
body{
  height: 100%;
  width: 100%;
  background-image: url('./assets/snow-ball-login-bg.jpg')
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 500px; */
}
</style>
