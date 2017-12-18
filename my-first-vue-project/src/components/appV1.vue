<template>

  <div class="app-v1">
    <p v-if="seen">看到我了吗???</p>

    <div class="app-v1">
      <p @click="doSomething">哈哈哈</p>
    </div>

    <div class="app-v1">
      <p>input 元素: </p>
      <input v-model="message" placeholder="编辑我...">
      <p>消息是: {{ message }} </p>

    </div>
  </div>

</template>

<script>
  export default {
    name: "",
    data () {
      return {
        seen: true,
        message: "Runoob"
      }
    },
    methods: {
      doSomething: function () {
        alert(1111)
      }
    }
  }
</script>
