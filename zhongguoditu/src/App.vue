<template>
  <nav>
    <!-- <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> -->
  </nav>
  <router-view/>


</template>

<style lang="less">
body{
  background:url("~@/assets/bj.png")top center no-repeat;
  background-size: cover;/* 使图片平铺满整个浏览器
  （从宽和高的最大需求方面来满足，会使某些部分无法显示在区域中） */
}
*{
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}
// #app {
//   font-family: Avenir, Helvetica, Arial, sans-serif;
//   -webkit-font-smoothing: antialiased;
//   -moz-osx-font-smoothing: grayscale;
//   text-align: center;
//   color: #2c3e50;
// }

// nav {
//   padding: 30px;

//   a {
//     font-weight: bold;
//     color: #2c3e50;

//     &.router-link-exact-active {
//       color: #42b983;
//     }
//   }
// }
</style>
