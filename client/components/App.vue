<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<style>
body {
  margin: 0;
  font-size: 1rem;
  font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;
}
.page {
  /* nesting for the need to test postcss */
  code {
    background-color: #f0f0f0;
    padding: 3px 5px;
    border-radius: 2px;
  }

  .content{
    width: 80%;
    max-width: 80rem;
    margin: 0 auto;
    -webkit-transition: all .4s;
    transition: all .4s;
    overflow: hidden;
  }

  ul{
    list-style: none;
    margin: 0;
    padding: 0;
  }
}


</style>
