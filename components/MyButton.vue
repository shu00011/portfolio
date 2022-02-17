<template>
  <div class="border-2 border-gray-600 bg-white text-gray-600 text-xs text-center py-2 px-4 w-40 h-38 rounded-full tracking-widest hover:bg-gray-600 hover:text-white" rel="noopener noreferrer">{{text}}</div>
</template>

<script>
export default {
  name: "MyButton",
  props:{
    text:{
      type: String,
    }
  },
}
</script>

<style scoped>

</style>
