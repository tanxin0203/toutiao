<template>
  <div id="app">
    <h1>黑马头条</h1>
    <van-button type="primary">主要按钮</van-button>
<van-button type="info">信息按钮</van-button>
<van-button type="default">默认按钮</van-button>
<van-button type="warning">警告按钮</van-button>
<van-button type="danger">危险按钮</van-button>
<div class="main"></div>
    <router-view/>
  </div>
</template>
<script>
export default {
  name: 'App'
}
</script>

<style lang="less">
.main{
  width: 200px;
  height: 100px;
  background: green;
}

</style>
