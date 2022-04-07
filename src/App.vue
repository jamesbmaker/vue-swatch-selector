<template>
  <div id="app">
    <SwatchSelector />
  </div>
</template>

<script>
import SwatchSelector from './components/SwatchSelector.vue'

export default {
  name: 'App',
  components: {
    SwatchSelector
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
}
</style>
