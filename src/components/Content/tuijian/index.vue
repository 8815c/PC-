<template>
      <!-- 推荐 -->
    <div class="tuijian">
      <ul class="ul2">
        <li class="li2">
          <img src="./images/01.jpg" alt="">
        </li>
        <li class="li2">
          <img src="./images/02.jpg" alt="">
        </li>
        <li class="li2">
          <img src="./images/03.png" alt="">
        </li>
        <li class="li2">
          <img src="./images/04.jpg" alt="">
        </li>
      </ul>
    </div>
</template>
<script>
export default {
  name:'tuijian'
}
</script>
<style lang='less' scoped>
  .tuijian{
    width: 1220px;
    height: 200px;
    background-color: cadetblue;
    margin: 30px auto 30px;
    border-radius: 16px;
    .ul2{
      
      .li2{
        width: 305px;
        height: 200px;
        background-color: pink;
        float: left;
        img{
          width: 305px;
          height: 200px;
        }
      }

    }
  }
</style>