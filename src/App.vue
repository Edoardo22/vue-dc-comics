<template>
  <div id="app">

    <TheNavbar></TheNavbar>
    <TheHeader></TheHeader>
    <TheBannerblue></TheBannerblue>
    <TheFooter></TheFooter>


  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheFooter from './components/TheFooter.vue'
import TheNavbar from './components/TheNavbar.vue'
import TheBannerblue from './components/TheBannerblue.vue'

export default {
  name: 'App',
  components: {
    TheHeader,
    TheFooter,
    TheNavbar,
    TheBannerblue
  }
}
</script>

<style lang="scss">
#app {}
</style>
