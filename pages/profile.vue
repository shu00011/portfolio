<template>
    <div class="relative grid grid-cols-12">
      <div class="text-gray-700 text-2xl grid md:col-start-5 md:col-end-6 z-20 left-8 top-5 absolute">
        <router-link to="/" class="mb-4">top</router-link>
        <router-link to="/works">works</router-link>
      </div>
      <h2 class="text-gray-400 text-4xl col-start-9 z-20 top-8 absolute md:col-start-8">about</h2>
      <img src="~/assets/sky.jpg" alt="profileimage" class="absolute rounded-t-lg top-14 col-start-2 col-end-11 sm:col-start-3 sm:col-end-11 md:col-start-5 md:col-end-9" />
      <div class="mt-10 sm:mt-0 absolute sm:top-96 top-72 text-gray-700 col-start-2 col-end-11 md:col-start-5 md:col-end-9 sm:col-start-3 sm:col-end-11">
        <p class="mb-2">名前：shu00011/<a href="https://oucrc.net/members/9svd4hgoy" target="_blank" rel="noopener noreferrer">小石こは</a></p>
        <p class="mb-2">所属：岡山大学工学部情報系学科3年/<br><a href="https://oucrc.net/" target="_blank" rel="noopener noreferrer">岡山大学電子計算機研究会(OUCRC)</a><br>(2021年度広報)</p>
        <p class="mb-2">趣味：写真</p>
        <p class="mb-2">技術：<br>HTML/CSS/C/Python/Flutter/Git/<br>JavaScript(Node/Vue/React/Next)</p>
        <a class="border-2 border-gray-600 bg-white text-gray-600 text-xs py-2 px-4 w-40 h-38 rounded-full tracking-widest hover:bg-gray-600 hover:text-white" href="https://github.com/shu00011" target="_blank" rel="noopener noreferrer">GitHubはこちら</a>
      </div>
    </div>
</template>

<script>
export default {
  data: function () {
    return {
      name: 'profile',
    }
  }
}
</script>

<style scoped>
h2{
  font-family:'Kiwi Maru',serif;
}
</style>
