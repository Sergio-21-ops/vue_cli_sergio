<template>
  <div id="app">
    <HelloWorld msg="Estamos probando vue 2 por cliS"/>
    <Contenido/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Contenido from './components/Contenido.vue'

export default {
  name: 'App',
  components: {
    Contenido,
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
</style>
