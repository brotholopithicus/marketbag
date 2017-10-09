<template>
  <div class="hello">
    <h1>Anya &amp; Greer Market Bag</h1>
    <h2>Slowing Down Fast Fashion</h2>
    <!-- <img src="../assets/image0007.jpg" /> -->
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img {
  max-width: 50%;
  height: auto;
  transform: rotate(270deg);
}
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
