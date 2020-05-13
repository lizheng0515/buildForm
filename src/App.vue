<template>
  <div id="app">
    <buildFrom/>
  </div>
</template>

<script>
import buildFrom from './components/buildFrom'

export default {
  name: 'App',
  components: {
    buildFrom
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
}
</style>
