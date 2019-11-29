<template>
  <div id="app">
     <router-view></router-view>
  
      <app-tab-bar></app-tab-bar>
  </div>
</template>

<script>
import AppTabBar from './components/MainTabBar/AppTabBar'
export default {
  name: "App",
  components: {
      AppTabBar
  }
};
</script>

<style>
@import "./assets/css/base.css";
@import "http://at.alicdn.com/t/font_1533831_amjhtkice1l.css";
</style>
