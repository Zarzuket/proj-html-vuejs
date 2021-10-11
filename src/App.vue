<template>
  <div id="app">
    <!-- <Header title="wewe"/> -->
    <Header/>

    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from "./components/Header.vue"

export default {
  name: 'App',
  components: {
    Header,
    // HelloWorld
  }
}
</script>

<style lang="scss">
@import "./assets/common";
@import '~@fortawesome/fontawesome-free/css/all.css';
</style>
