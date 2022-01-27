<template>
  <div id="app">
      <header-box />
      <jumbotron-box />
      <section-items />
  </div>
</template>

<script>
import headerBox from './components/headerBox.vue'
import jumbotronBox from './components/jumbotronBox.vue'
import sectionItems from './components/sectionItems.vue'

export default {
  name: 'App',
  components: {
    headerBox,
    jumbotronBox,
    sectionItems
  }
}
</script>

<style lang="scss">

  @import '@/style/main.scss';
  
  
</style>
