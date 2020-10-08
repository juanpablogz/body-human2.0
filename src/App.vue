<template>
  <div id="app">
    <bodyhuman/>
  </div>
</template>

<script>
import bodyhuman from './components/body-human/body-human'
export default {
  name: 'App',
  components: {
    bodyhuman
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
