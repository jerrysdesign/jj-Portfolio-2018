<template lang="pug">
  #app
    TopNav
    router-view
</template>


<script>
import TopNav from '@/components/TopNav'

export default {
  name: 'app',
  components: {
    TopNav
  }
}
</script>


<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
