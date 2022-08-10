<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <Navbar/>
  <FooterComp/>
</template>

<script>
import Navbar from './components/Navbar.vue'
import FooterComp from './components/FooterComp.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    FooterComp
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
</style>
