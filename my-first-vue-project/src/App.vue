<template>

  <div id="app">
    <img src="./assets/logo.png">
    <!-- 组件导入 -->
    <HelloWorld/>
    <appV1/>
  </div>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import appV1 from './components/appV1.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    appV1
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
