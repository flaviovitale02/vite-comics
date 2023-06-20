<script>

import Header from "./components/AppHeader.vue"
import Main from "./components/AppMain.vue"
import Footer from "./components/AppFooter.vue"

export default {
  name: "App",

  components:{
    Header,
    Main,
    Footer
  }
}

</script>

<template>
    <Header/>
    <Main/>
    <Footer/>
</template>

<style lang="scss" >
  @import './styles/general.scss'
</style>
