<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  list-style: none;
}

* a {
  text-decoration: none;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  height: 100%;
}
.el-container .el-header {
  padding: 0px;
}
.el-container .el-main {
  padding: 0px;
}
.el-container .el-footer {
  padding: 0px;
}
</style>
