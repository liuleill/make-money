<template>
<div id="app">
      <router-view/>
      <hr/> 
</div>
</template>

<style lang="scss">
@import "~@/assets/style/helper.scss";
@import "~@/assets/style/reset.scss";
body {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  line-height:1.5;
  font-family: $font-hei;  
  font-size: 16px;
  color:#333;
  background:#f5f5f5;
}
</style>
