<template>
  <div id="app">
    <!--<img src="./assets/logo.png">-->
    <v-header/>
    <div class="tab">
      <div class="tab-item">商品</div>
      <div class="tab-item">评论</div>
      <div class="tab-item">商家</div>
    </div>
    <!--<router-view/>-->
  </div>
</template>

<script>
  import Header from './components/header/header';

  export default {
    components: {'v-header': Header},
    name: 'App'
  };
</script>

<style lang="stylus" rel="stylesheet/stylus" scoped>
  #app
    .tab
      display: flex
      width: 100%
      height: 40px
      line-height: 40px
    .tab-item
      flex: 1
      text-align: center
</style>
