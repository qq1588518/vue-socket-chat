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

<style>
body,html{
  height: 100%;
}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body{
  font-size: 14px;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  height: 100%;
}
button{
  outline: none;
  border: none;
}
</style>
