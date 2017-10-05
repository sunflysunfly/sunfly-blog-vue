<template>
  <div id="app">
    <blog-header></blog-header>
    <router-view></router-view>
  </div>
</template>

<script>
import Header from "./components/Header";
export default {
  name: 'app',
  components:{
    blogHeader:Header
  }
}
</script>

<style>
body{background:#f7fae3}
@import "../static/css/public.css";
@import "../static/font/iconfont.css"
</style>
