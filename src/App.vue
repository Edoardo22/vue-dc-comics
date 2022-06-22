<template>
  <div id="app">

    <TheNavbar></TheNavbar>
    <TheMain></TheMain>
    <TheBannerblue></TheBannerblue>
    <TheFooter></TheFooter>
    <BannerFooter></BannerFooter>


  </div>
</template>

<script>
import TheMain from './components/TheMain.vue'
import TheFooter from './components/TheFooter.vue'
import TheNavbar from './components/TheNavbar.vue'
import TheBannerblue from './components/TheBannerblue.vue'
import BannerFooter from './components/bannerFooter.vue'

export default {
  name: 'App',
  components: {
    TheMain,
    TheFooter,
    TheNavbar,
    TheBannerblue,
    BannerFooter
  }
}
</script>

<style lang="scss">
#app {}
</style>
