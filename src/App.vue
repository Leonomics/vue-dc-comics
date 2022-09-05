<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png">-->
    <!--<HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <HeaderItem></HeaderItem>
    <MainItem></MainItem>
  </div>
</template>

<script>
import HeaderItem from './components/HeaderItem.vue'
import MainItem from './components/MainItem.vue'
//import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld,
    HeaderItem,
    MainItem,
}
}
</script>

<style lang="scss">
  @import './style/index';
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
