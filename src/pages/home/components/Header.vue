<template>
  <div class="header">
      <div class="header-left">返回</div>
      <div class="header-input">输入城市经典游玩主题</div>
      <div class="header-right">城市</div>
  </div>
</template>

<script>

export default {
}
</script>

<style lang="stylus" scoped>
  .header
    display: flex
    line-height: .86rem
    background: #00bcd4
   .header-left
     float:left
     width:.64rem
   .header-input
     flex:1
     margin-top: .12rem
     height:.64rem
     margin-left:.2rem
     background:#fff
     border-radius:.1rem
     color : #ccc
     line-height:.64rem
   .header-right
     float:right
     width: 1.24rem
     text-align: center
</style>
