<template>
  <div id="app">
    <header-box />
    <main-content />
    <navbar-shop />
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import MainContent from './components/MainContent.vue'
import NavbarShop from './components/NavbarShop.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    MainContent,
    NavbarShop,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
