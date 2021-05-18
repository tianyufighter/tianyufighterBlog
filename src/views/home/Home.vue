<template>
  <div>
    <top-bar></top-bar>
    <nav-bar></nav-bar>
  </div>
</template>

<script>
import TopBar from "./childComps/TopBar";
import NavBar from "./childComps/NavBar";
export default {
  name: "Home",
  components: {
    TopBar,
    NavBar
  }
}
</script>

<style scoped>

</style>