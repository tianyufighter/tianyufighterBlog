<template>
  <div id="app">
    <router-link to="/"></router-link>
    <router-view/>
  </div>
</template>
<script>
export default {
  name: "app"
}
</script>

<style lang="scss">
@import "assets/css/base.css";
/*设置body标签的样式*/
html,body {
  height: 100%;
}
</style>
