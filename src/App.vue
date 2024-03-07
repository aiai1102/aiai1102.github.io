<template>
  <TabMenu />
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <img alt="Vue logo" src="./assets/horse2.jpg">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <HelloWorld msg="ﾃｽﾄ①"/></template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TabMenu from './components/TabMenu.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TabMenu
  }
}

</script>

<!-- <script>
import TabMenu from './components/TabMenu.vue'
export default {
  name: 'App',
  components: {
    TabMenu
  }
}
</script> -->


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
