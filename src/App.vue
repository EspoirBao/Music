<template>
  <div id="app">
    <div class="banner">
      <span class="L">网易云音乐</span>
      <span class="R">下载app</span>
    </div>
    <div id="nav">
      <van-tabs v-model="active">
        <van-tab title="Home"></van-tab>
        <van-tab title="About"></van-tab>
        <van-tab title="search"></van-tab>
        
      </van-tabs>
      
      
      
    </div>
    <router-view />
  </div>
</template>
<script>
import Vue from "vue";
export default {};
</script>
<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.banner{
  height: 0.85rem;
  width: 100%;
  background: #d43c33;
  display: flex;
  justify-content: space-around;
  padding: 0 0.1rem;
  .span{
    color: #fff;
    font-size: 24px;
  }
  .L{
    
  }
  .R{

  }

}
#nav {
  
  
 
}
</style>
