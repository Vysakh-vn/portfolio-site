<template>
  <Navbar/>
  <MainContainer/>
</template>

<script>
import Navbar from './components/NavBar.vue'
import MainContainer from './components/MainContainer.vue'

export default {
  name: 'App',
  components: {
    Navbar, MainContainer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  height: 100vh;
  background-color: #F0F2F5;
}
</style>
