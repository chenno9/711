<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
/* #app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  html,body,#app{
    height: 100%;
  }
  ul,li {
    list-style: none;
  }
  a{
    text-decoration:none;
    outline: none;
    color: #fff;
  }
  #app{
    width: 100%;
  }
</style>
