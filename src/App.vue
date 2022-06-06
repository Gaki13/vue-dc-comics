<template>
  <div id="app">
    <BaseHeader/>
    <ComponentJumbo/>
    <BaseMain/>
    <TopFooter/>
    <MiddleFooter/>
    <BottomFooter/>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader/BaseHeader.vue'
import ComponentJumbo from './components/BaseMain/ComponentJumbo.vue'
import BaseMain from './components/BaseMain/ComponentMain.vue'
import TopFooter from './components/BaseFooter/TopFooter.vue'
import MiddleFooter from './components/BaseFooter/MiddleFooter.vue'
import BottomFooter from './components/BaseFooter/BottomFooter.vue'

export default {
  name: 'App',
  components: {
    BaseHeader,
    ComponentJumbo,
    BaseMain,
    TopFooter,
    MiddleFooter,
    BottomFooter,
  }
}
</script>

<style lang="scss">
  @import './assets/style/global.scss'
</style>
