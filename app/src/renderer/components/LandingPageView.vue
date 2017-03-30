<template>
    <div>
        <img src="./LandingPageView/assets/logo.png" alt="electron-vue">
        <h1>Welcome.</h1>
        <hr>
        <current-page></current-page>
        <versions></versions>
        <links></links>
        <hr>
        <navigator></navigator>
        <hr>
    </div>
</template>

<script>
  import CurrentPage from './LandingPageView/CurrentPage'
  import Links from './LandingPageView/Links'
  import Versions from './LandingPageView/Versions'
  import Navigator from './Shared/Navigator'

  export default {
    components: {
      Navigator,
      CurrentPage,
      Links,
      Versions
    },
    name: 'landing-page'
  }
</script>

<style scoped lang="scss">
    img {
        margin-top: -25px;
        width: 450px;
    }
</style>
