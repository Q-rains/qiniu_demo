<template>
  <div id="app">
    <img src="./assets/logo.png"><br/>
    路由列表：<br/>
    <router-link to='/el_upload'>使用饿了么组件el-upload，上传到七牛</router-link><br/>
    <router-link to='/'>多个js-sdk上传：包含多个upload子组件</router-link><br/>
    <router-link to='/multiformdata'>多个formdata上传：包含多个formdata子组件</router-link><br/>
    <router-link to='/hello'>hello页面</router-link><br/>
    <div>============以下是内容=============</div>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
