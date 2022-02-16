<template>
  <div class="relative grid grid-cols-12">
    <div class="text-gray-700 text-2xl grid md:col-start-5 md:col-end-6 z-10 left-8 top-5 absolute">
      <router-link to="/profile" class="mb-4">about</router-link>
      <router-link to="/works">works</router-link>
    </div>
    <img src="~/assets/tokyo.jpg" alt="topimage" class="rounded-full absolute top-14 sm:col-start-3 sm:col-end-11 lg:col-start-5 lg:col-end-9 sm:col-span-full" />
    <h1 class="text-white top-96 left-4 text-6xl absolute z-10 md:col-start-5 text-gray-200">shu00011</h1>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      title: 'Hello, World!!',
    }
  },
}
</script>

<style>
h1{
  font-family:'Kiwi Maru',serif;
}
</style>
