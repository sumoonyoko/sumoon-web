<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<style>
  .hello {
    background: url("//game.gtimg.cn/images/yxzj/coming/v2/skins//image/20201215/16080207907887.jpg") no-repeat;
    background-size: cover;
    height: 870px;
  }
</style>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: '欢迎来到王者荣耀'
    }
  }
}
</script>
