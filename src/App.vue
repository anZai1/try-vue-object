<template>
  <div id="app">
    <el-container>
      <LeftNav></LeftNav>
      <HeaderBar></HeaderBar>
    </el-container>
  </div>
</template>

<script>
import HeaderBar from "./components/HeaderBar.vue";
import LeftNav from "./components/LeftNav.vue";
export default {
  components: {
    HeaderBar,
    LeftNav,
  },
};
</script>

<style>
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
