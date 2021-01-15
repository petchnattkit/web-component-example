<template>
  <div id="app">
    <input-web-component msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import InputWebComponent from './components/InputWebComponent.vue'

export default {
  name: 'App',
  components: {
    InputWebComponent
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
