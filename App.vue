<template>
  <div id="app">
    <Project/>
  </div>
</template>

<script>
import Project from './components/Project.vue'

export default {
  name: 'app',
  components: {
    Project
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
  margin-top: 60px;
}
</style>
