<template>
  <div id="app">
    <titolo/>
    <hero class="image"/>
  </div>
</template>

<script>
import titolo from './components/title.vue'
import hero from './components/hero.vue'

export default {
  name: 'App',
  components: {
    titolo,
    hero
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
.image{
  margin-top: 6rem;
}
</style>
