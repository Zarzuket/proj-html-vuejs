<template>
  <div id="app">
    <!-- <Header title="wewe"/> -->
    <Header/>
    <SectionAward/>
    <SectionService/>
    <Main/>
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
export default {
  name: 'App',
  components: {
    Header,
    SectionAward,
    SectionService,
    Main
    // HelloWorld
  }
}
</script>

<style lang="scss">
@import "./assets/common";
@import '~@fortawesome/fontawesome-free/css/all.css';
</style>
