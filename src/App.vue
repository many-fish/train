<template>
  <div id="app">
    <Index/>
  </div>
</template>

<script>
import Index from './components/index.vue'

export default {
  name: 'app',
  components: {
    Index
  }
}
</script>

<style lang="scss">
  @import "./assets/scss/index.scss";
</style>
