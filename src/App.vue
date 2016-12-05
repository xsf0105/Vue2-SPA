<template>
  <div id="app">
    <img src="./assets/logo.png">
    <hello></hello>
    <p>
      <router-link to="/index">点我跳转到第一页</router-link>
      <router-link to="/second">点我跳转到第二页</router-link>
    </p>
    <router-view class="view"></router-view>
  </div>
</template>

<script>
import Hello from './components/Hello'
export default {
  name: 'app',
  components: {
    Hello
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







