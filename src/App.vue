<template>
  <div id="app">
    <Webstore />
  </div>
</template>

<script>
import Webstore from './components/Webstore.vue'

export default {
  name: 'App',
  components: {
    Webstore
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
