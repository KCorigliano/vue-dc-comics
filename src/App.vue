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
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
