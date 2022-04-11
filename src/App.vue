<template>
  <div id="app">
    <TitleComp></TitleComp>
    <HeroJumbotron></HeroJumbotron>
  </div>
</template>

<script>
import TitleComp from './components/TitleComp.vue'
import HeroJumbotron from './components/HeroJumbotron.vue'

export default {
  name: 'App',
  components: {
    TitleComp,
    HeroJumbotron
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
