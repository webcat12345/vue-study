<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App" title="This component is First vue component"/>
    <Sidebar v-bind:status="true"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Sidebar from './components/Sidebar';

export default {
  name: 'app',
  components: {
    HelloWorld,
    Sidebar
  },
  methods: {

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
