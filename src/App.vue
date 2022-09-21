<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TitleApp/>
    <HeroApp/>
  </div>
</template>

<script>
import TitleApp from './components/titleApp.vue';
import HeroApp from './components/HeroApp.vue';


export default {
  name: 'App',
  components: {
    TitleApp,
    HeroApp
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
