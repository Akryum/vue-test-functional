<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>Testing</h1>
    <h2>Essential Links</h2>
    <p>Functional components</p>
    <Test/>
  </div>
</template>

<script>
import Test from './Test.vue'

export default {
  name: 'app',
  components: {
    Test,
  },
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

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
