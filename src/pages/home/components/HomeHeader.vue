<template>
  <div class="header">
    <div class="header-left"><i class="iconfont iconjiantou2"></i></div>
    <div class="header-search">
      <i class="iconfont iconfangdajing"></i>
      请输入城市名称或关键字
    </div>
    <div class="header-right">广州</div>
  </div>
</template>

<script>
  import '@/assets/fonts/iconfont/iconfont.css'
  export default {
    name: "HomeHeader"
  }
</script>

<style lang="less" scoped>
  .header{
    display:flex;
    align-items: center;
    height:86px;
    line-height:86px;
    background:#42B983;
    .header-left{
      width:64px;
      text-align: center;
      i{
        font-size:45px
      }
    }
    .header-search{
      flex: 1;
      height:64px;
      line-height:64px;
      color:#969896;
      margin-left:20px;
      background:#fff;
      padding:0 10px;
      border-radius:30px;
      i{
        font-size:35px
      }
    }
    .header-right{
      // width:140px;
      margin:0 20px;
      color:#fff;
      text-align: center
    }
  }
</style>
