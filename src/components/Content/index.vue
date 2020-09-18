<template>
  <div>
    <Banner></Banner>
    <Tuijian></Tuijian>
  </div>
</template>
<script>
import Banner from './banner/index'
import Tuijian from './tuijian/index'
export default {
  name:'banner',
  components:{
    Banner,
    Tuijian
  }
};
</script>
<style lang="less" scoped>

</style>
