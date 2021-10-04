<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Formulari msg="Asín andaba yo de siego por la vida"/>
  </div>
</template>

<script>
import Formulari from './components/Formulari.vue'

export default {
  name: 'App',
  components: {
    Formulari
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
