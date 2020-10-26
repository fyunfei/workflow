<template>
  <div id="app">
    <h1 style="text-align:center">
      Quill 自定义样式+扩展（{{ new Date() }}）修改
    </h1>
    <router-view />
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
