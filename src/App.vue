<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TitoloComp></TitoloComp>
  </div>
</template>

<script>
import TitoloComp from './components/Titolo.vue'

export default {
  name: 'App',
  components: {
    TitoloComp
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
