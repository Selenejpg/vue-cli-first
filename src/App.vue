<template>
  <div id="app">
    <img class="montagna" alt="Vue logo" src="./assets/Fronalpstock_big.jpeg">
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
}
.montagna{
  width: 100vw;
  margin: 0;
}
</style>
