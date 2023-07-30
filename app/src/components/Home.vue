<template>
  <div class="hello">
    <h1 style="font-family: cursive;">一辣一辣</h1>
    <p>网站正在建设中...</p>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
h1 {
  padding-top: 50px;
}
p {
  padding-top: 50px;
  border-bottom: 1px dashed #c6c6c6;
}
</style>
