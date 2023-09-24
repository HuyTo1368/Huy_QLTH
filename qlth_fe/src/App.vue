<template>
  <div>
    <TheIndex />
  </div>
</template>

<script>
import TheIndex from './pages/Login/MLogin.vue'

export default {
  name: 'App',
  components: {
    TheIndex
  }
}
</script>

<style>
@import url(../src/css/main.css);
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
}
</style>
