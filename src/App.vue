<template>
  <div id="app">
    <el-container>
      <el-header>
        <el-row>
          <el-col :span="24">
            <el-menu default-active="4" mode="horizontal" @select="handleSelect">
              <el-menu-item index="1">高级插件</el-menu-item>
              <el-menu-item index="2">在线商城</el-menu-item>
              <el-menu-item index="3">客户管理</el-menu-item>
              <el-menu-item index="4">系统设置</el-menu-item>
              <el-menu-item index="5">活动发布</el-menu-item>
            </el-menu>
          </el-col>
        </el-row>
      </el-header>
      <el-main>Main</el-main>
    </el-container>
  </div>
</template>

<script>
  import Vue from 'vue'
  import ElementUI from 'element-ui'
  import 'element-ui/lib/theme-chalk/index.css'

  Vue.use(ElementUI)
  export default {
    name: 'App'
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
