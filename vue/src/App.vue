<template>
  <div id="app">
    <h2> {{ msg }} </h2>
    <div class="wrap">
      <div class="left-container">
        <p>contents</p>
      </div>
      <div class="right-container">
        <img src="../../image/lifecycle.png">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>
.wrap {
  width: 100%;
  display: flex;
}
h2 {
  text-align: center;
}
.left-container {
  width: 50%;
  text-align: center;
}
.right-container {
  width: 50%;
  text-align: center;
}
img {
  width: 30%;
}
</style>
