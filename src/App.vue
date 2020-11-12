<template>
  <div id="app">
    <h1>黑马头条</h1>
    <!-- 路由的出口 -->
    <router-view/>
  </div>
</template>

<script>
export default {
  // 写这个名字是为了在google浏览器中的vue调试工具中可以用名字搜索到
  name:'App'
}
</script>



<style lang="less">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
