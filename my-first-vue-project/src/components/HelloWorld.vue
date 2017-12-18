<template>

  <div class="hello">
    <label for="r1" v-html="msg"></label><input type="checkbox" v-model="class1" id="r1">
    <br><br>
    <div v-bind:class="{'class1': class1}">
      directiva v-bind:class
    </div>
  </div>

</template>

<script>
export default {
  name: "",
  data () {
    return {
      msg: "<h1 style='color: red'>欢迎来到菜鸟教程！</h1>",
      class1: false
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
.class1 {
  color: rebeccapurple;
}
</style>
