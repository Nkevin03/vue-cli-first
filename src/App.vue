<template>
  <div id="app">
    <Header />
    <Hero />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    Header,
    Hero
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
