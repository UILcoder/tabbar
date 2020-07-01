<template>
  <div id="app">
    <router-view/>
    <MainTabbar/>
  </div>
</template>

<script>
import MainTabbar from './components/MainTabbar'
//或者导入TabBar、TabBarItem相对应模板中的tab-bar、tab-bar-item  
export default {
  name: 'App',
  components: {
    MainTabbar
  }
}
</script>

<style>
  @import './assets/css/base.css';
</style>
