<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <h2>{{title}}</h2>
  </div>
</template>

<script>
export default {
  data () {
    return {
      title: 'Hello World'
    }
  },
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
