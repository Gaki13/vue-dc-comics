<template>
  <div id="app">
    <BaseHeader/>
    <BaseMain/>
    <TopFooter/>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader/BaseHeader.vue'
import BaseMain from './components/BaseMain/ComponentMain.vue'
import TopFooter from './components/BaseFooter/TopFooter.vue'

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    TopFooter,
  }
}
</script>

<style lang="scss">
@import './assets/style/global.scss'
</style>
