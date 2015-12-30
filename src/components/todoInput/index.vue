<style src="./style" scoped></style>

<template>
  <input placeholder="What needs to be done?"
    @keydown.enter="handleSubmit" v-model="text" />
</template>

<script>
  export default {
    data () {
      return {
        text: ''
      }
    },
    methods: {
      handleSubmit () {
        console.log(this.text)
        this.text = ''
      }
    }
  }
</script>
