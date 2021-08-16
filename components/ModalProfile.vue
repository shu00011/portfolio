<template>
  <div class="component">
    <button v-on:click="alert">emitを使おう！</button>
  </div>
</template>

<script>
export default {
  name: "ModalProfile",
  methods:{
    alert(){
      //alert('Hello, Nuxt.js!')
      this.$emit('componentAlert')
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
