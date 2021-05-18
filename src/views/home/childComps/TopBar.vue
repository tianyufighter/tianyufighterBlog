<!--首页顶部图片-->
<template>
  <div class="top">
    <img src="~assets/img/homeTopBar.jpg" alt=""/>
  </div>
</template>

<script>
export default {
  name: "TopBar"
}
</script>

<style scoped>
  .top {
    background-color: #ff8198;
    height: 30vh;
  }
  /*设置图片的大小*/
  .top > img {
    height: 100%;
    width: 100%;
  }
</style>