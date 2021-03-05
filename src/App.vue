<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <h1>ref:</h1>
  <Demo />
  <h1>ref()</h1>
  <Demo2 />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Demo from './components/Demo'
import Demo2 from './components/Demo2'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Demo,
    Demo2
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
