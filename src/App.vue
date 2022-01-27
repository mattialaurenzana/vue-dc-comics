<template>
  <div id="app">
      <header-box />
  </div>
</template>

<script>
import headerBox from './components/headerBox.vue'

export default {
  name: 'App',
  components: {
    headerBox
  }
}
</script>

<style lang="scss">

  @import '@/style/main.scss';
  
  
</style>
