<template>
  <div id="app">
    <main-page msg="Welcome to Your Vue.js App"/>
  </div>
</template>


<script>

import MainPage from '@/components/MainPage.vue'

export default {
  name: 'App',
  components: { MainPage },
}
</script>


<style>

body {
  height: 100vh;
  width: 100vw;
  margin: 0;
}

#app {
  height: 100vh;
  width: 100vw;
  color: #2c3e50;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
