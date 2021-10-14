<template>
  <div id="app">
    <!-- <Header title="wewe"/> -->
    <Header/>
    <SectionAward/>
    <SectionService/>
    <Main/>
    <SectionReviews/>
    <RecentBlog/>
    <Footer/>
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from "./components/Header.vue"
import SectionAward from "./components/SectionAward.vue"
import SectionService from "./components/SectionService.vue"
import Main from "./components/Main.vue"
import SectionReviews from "./components/SectionReviews.vue"
import RecentBlog from "./components/RecentBlog.vue"
import Footer from "./components/Footer.vue"
export default {
  name: 'App',
  components: {
    Header,
    SectionAward,
    SectionService,
    Main,
    SectionReviews,
    RecentBlog,
    Footer
    // HelloWorld
  }
}
</script>

<style lang="scss">
@import "./assets/common";
@import '~@fortawesome/fontawesome-free/css/all.css';
</style>
