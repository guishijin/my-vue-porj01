<template>
  <div id="app">
    <img src="./assets/logo.png">
    <Hello></Hello>
    <hr />
    <calculator></calculator>
    <calculator></calculator>
    <calculator></calculator>
    <calculator></calculator>
    <hr />
    <br />
    <HelloWorld></HelloWorld>
    <hr />
    <br />
  </div>
</template>

<script>
import Hello from './components/Hello'
import HelloWorld from './components/HelloWorld'
import calculator from './components/calculator'

export default {
  name: 'App',
  components: {
    Hello,
    HelloWorld,
    calculator
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
