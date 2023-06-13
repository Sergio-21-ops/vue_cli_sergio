<template>
  <div id="app">
    <HelloWorld msg="Estamos probando vue 2 por cliS"/>
    <Contenido_app/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Contenido_app from './components/Contenido_app.vue'

export default {
  name: 'App',
  components: {
    Contenido_app,
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
