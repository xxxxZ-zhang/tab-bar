<template>
  <div id="app">
    <router-view></router-view>
    <main-tab-bar></main-tab-bar>
    
  </div>
</template>
<script>
import router from './router';
import MainTabBar from './components/MainTabBar';
export default {
  components: {
    MainTabBar
  },
};
</script>
<style>
@import "./assets/css/base.css";

</style>
