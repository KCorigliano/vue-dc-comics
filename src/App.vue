<template>
  <div id="app">
    <header-box />
    <main-content />
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import MainContent from './components/MainContent.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    MainContent,
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
