<!--
 * @Author: zequan.wu
 * @Date: 2022-09-19 15:28:14
 * @LastEditors: zequan.wu
 * @LastEditTime: 2022-09-19 15:37:45
 * @FilePath: \git-changelog\src\App.vue
 * @Description: 
 * 
-->
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <div>改一下</div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

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
