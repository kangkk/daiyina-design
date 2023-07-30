<template>
  <div class="main">
    <img class="img" alt="一辣一辣" src="./assets/daiyina-1.jpeg">
    <HomePage />
  </div>
</template>

<script>
import HomePage from './components/Home.vue'

export default {
  name: 'App',
  components: {
    HomePage
  }
}
</script>

<style>
#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.main {
  display: flex;
  padding: 50px;
}
.img {
  width: 400px;
  padding-right: 50px;
}
</style>
