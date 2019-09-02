<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{ msg }}</h1>

    <p > {{ sum }} </p>

    my result is: <h1> {{ info }} </h1>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'hi',
      sum: 10,
      info: ''
    }
  },
  created() {
      console.log("created");
  },
  mounted() {
    if (this.sum == 100) {
      this.info = "success"
    } else {
      this.info = "fail"
    }
    console.log("mounted")
  }
}
</script>

