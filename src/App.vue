<template>
  <div>
    <router-view/>
    <FooterGuide/>
  </div>
</template>
<script>
import FooterGuide from './components/FooterGuide/FooterGuide'
export default {
  comments: {
    FooterGuide
  }
}
</script>
<style lang="stylus" rel="stylesheet/stylus" scoped>
  #app
    color red
</style>
