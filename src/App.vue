<template>
  <div id="app">
    <webview id="foo" src="https://admin:2222@tech-flow.herokuapp.com/" style="display:inline-flex; width:100vw; height:100vh"></webview>
    <!-- <webview id="foo" src="http://admin:2222@localhost:3000/" style="display:inline-flex; width:100vw; height:100vh"></webview> -->
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
html {
    height: 100%;
    width: 100%
}
body {
    margin: 0;
    height: 100%;
    width: 100%;
    background-color: rgb(0, 0, 0);

}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
