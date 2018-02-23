<template lang="pug">
  .header
    header
      router-link(to="/")
        .logo JJ
      nav
        ul
          li: router-link(to='/home') HOME
          li: router-link(to='/about') ABOUT
          li: router-link(to='/experiences') EXPERIENCES
          li: router-link(to='/education') EDUCATION
          li: router-link(to='/portfolio') PORTFOLIO
          li: router-link(to='/contact') CONTACT
      .more-back-links
        router-link(to="/")
          | {{ goHome }}
        router-link(to='/about')
          | {{ goAbout }}
</template>


<script>
  export default {
    name: 'topnav',
    data: () => {
      return {
        goHome: 'Back to home',
        goAbout: 'More about me'
      }
    }
  }
</script>


<style lang="scss" scoped>
</style>
