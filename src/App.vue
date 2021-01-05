<template>
  <div id="app">
    <home></home>
    <router-view/>
  </div>
</template>

<script>
// 导入组件
import Home from './components/Home'

export default {
  name: 'App',
  components: {
    Home
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
  height: auto;
  margin-top: 83px;
}
</style>
