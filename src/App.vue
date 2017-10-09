<template>
<div id="app">
  <div class="container">
    <hello-world/>
  </div>
</div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
* {
  box-sizing: border-box;
}

:root {
  /*--bg-overlay: rgba(184, 163, 121, 0.35);*/
  --bg-overlay: rgba(184, 163, 121, 0.3);
}

html {
  background: linear-gradient( var(--bg-overlay),
  var(--bg-overlay)), url(./assets/image0006_270.jpg) no-repeat center center fixed;
  background-size: cover;
}

html,
body {
  margin: 0;
  padding: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
