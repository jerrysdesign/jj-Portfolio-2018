<template lang="pug">
  .page.page-about
    h1 {{ pageName }}
</template>


<script>
export default {
  name: 'about',
  data: () => {
    return {
      pageName: 'About'
    }
  }
}
</script>


<style lang="scss" scoped>
</style>
