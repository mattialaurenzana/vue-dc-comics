<template>
  <div id="app">
      <header-box />
      <jumbotron-box />
      <section-items />
      <footer-box />
      <last-box />
  </div>
</template>

<script>
import headerBox from './components/headerBox.vue'
import jumbotronBox from './components/jumbotronBox.vue'
import sectionItems from './components/sectionItems.vue'
import footerBox from './components/footerBox.vue'
import lastBox from './components/lastBox.vue'

export default {
  name: 'App',
  components: {
    headerBox,
    jumbotronBox,
    sectionItems,
    footerBox,
    lastBox
  }
}
</script>

<style lang="scss">

  @import '@/style/main.scss';
  
  
</style>
