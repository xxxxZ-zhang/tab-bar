<template>
  <tab-bar>
      <tab-bar-item path='/home' activeColor="blue">
        <div slot="item-icon">
          <img src="../assets/img/tabbar/home.svg" alt="">
        </div>
        <div slot="item-icon-active">
          <img src="../assets/img/tabbar/home_active.svg" alt="">
        </div>
        <div slot="item-text">首页</div>
      </tab-bar-item>
    </tab-bar>
</template>

<script>
import TabBar from "./tabbar/TabBar";
import TabBarItem from './tabbar/TabBarItem';
export default {
  name: 'MainTabBar',
  data() {
    return {}
  },
  components: {
    TabBar,
    TabBarItem
  }
}
</script>

<style scoped>

</style>