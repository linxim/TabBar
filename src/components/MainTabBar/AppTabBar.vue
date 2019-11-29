<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="#22C7F1">
      <i slot="item-icon" class="iconfont iconshouye"></i>
      <i slot="item-icon-active" class="iconfont iconshouye1"></i>
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category" activeColor="#22C7F1">
      <i slot="item-icon" class="iconfont iconfenlei"></i>
      <i slot="item-icon-active" class="iconfont iconfenlei1"></i>

      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/shopcart" activeColor="#22C7F1">
      <i slot="item-icon" class="iconfont icongouwuche"></i>
      <i slot="item-icon-active" class="iconfont icongouwuche1"></i>

      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile" activeColor="#22C7F1">
      <i slot="item-icon" class="iconfont iconweibiaoti-"></i>
      <i slot="item-icon-active" class="iconfont iconwode"></i>

      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>
<script>
import TabBar from "@/components/tabbar/TabBar";
import TabBarItem from "@/components/tabbar/TabBaritem";
export default {
    name:"AppTabBar",
    components:{
        TabBar,
        TabBarItem
    }
};
</script>
<style scoped>

</style>