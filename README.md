# tabbar

## MainTabBar 配置
```
<tab-bar>
  <tab-bar-item path='/home' activeColor="red">
    <div slot="item-icon">
      <img src="../assets/img/tabbar/home.svg" alt="">
    </div>
    <div slot="item-icon-active">
      <img src="../assets/img/tabbar/home_active.svg" alt=""> 
    </div>
    <div slot="item-text">首页</div>
  </tab-bar-item>
</tab-bar>
```
### 选项
* path: 路由
* activeColor: 当前活跃tab-bat-item字体颜色，默认红色
* src: 图片路径

## app.vue 引入
```
import MainTabBar from './components/MainTabBar
export default {
  components: {
    MainTabBar
  }
}

```
