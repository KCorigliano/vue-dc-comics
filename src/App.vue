<template>
  <div id="app">
    <header-box />
    <main-content />
    <navbar-shop />
    <footer-box />
    <footer-nav />
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import MainContent from './components/MainContent.vue'
import NavbarShop from './components/NavbarShop.vue'
import FooterBox from './components/FooterBox.vue'
import FooterNav from './components/FooterNav.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    MainContent,
    NavbarShop,
    FooterBox,
    FooterNav
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
