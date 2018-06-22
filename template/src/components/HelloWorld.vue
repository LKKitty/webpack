<template>
  <div class="hello">
    <h1>\{{msg}}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '小二自定义的vue-cli模板哟，欢迎使用'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  width: 100vw;
  height: 100vh;
}
h1 {
  font-weight: bolder;
  color: #42b983;
 font-size: 48px;
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
