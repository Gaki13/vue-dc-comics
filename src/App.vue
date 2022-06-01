<template>
  <div id="app">
    <BaseHeader/>
    <BaseMain/>
    <TopFooter/>
    <MiddleFooter/>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader/BaseHeader.vue'
import BaseMain from './components/BaseMain/ComponentMain.vue'
import TopFooter from './components/BaseFooter/TopFooter.vue'
import MiddleFooter from './components/BaseFooter/MiddleFooter.vue'

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    TopFooter,
    MiddleFooter,
  }
}
</script>

<style lang="scss">
@import './assets/style/global.scss'
</style>
