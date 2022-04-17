<template>
    <div class="relative grid grid-cols-12">
      <div class="text-gray-700 text-2xl grid md:col-start-5 md:col-end-6 z-20 left-8 top-5 absolute">
        <router-link to="/" class="mb-4">top</router-link>
        <router-link to="/works">works</router-link>
      </div>
      <h2 class="text-gray-400 text-4xl col-start-9 z-20 top-8 absolute md:col-start-8">about</h2>
      <img src="~/assets/sky.jpg" alt="profileimage" class="myimg absolute rounded-t-lg top-14 col-start-2 col-end-12 sm:col-start-3 sm:col-end-11 md:col-start-5 md:col-end-9" />
      <div class="mt-10 sm:mt-0 absolute sm:top-96 top-72 md:left-8 text-gray-700 col-start-2 col-end-11 md:col-start-5 md:col-end-9 sm:col-start-3 sm:col-end-11">
        <p class="mb-2">名前：shu00011/<a class="underline" href="https://oucrc.net/members/9svd4hgoy" target="_blank" rel="noopener noreferrer">小石こは</a></p>
        <p class="mb-2">所属：岡山大学工学部情報系学科4年/<br><a class="underline" href="http://www.momo.cs.okayama-u.ac.jp/~zeynep/students.html" target="_blank" rel="noopener noreferrer">人間行動分析学研究室</a>/<br><a href="https://oucrc.net/" target="_blank" rel="noopener noreferrer">岡山大学電子計算機研究会(OUCRC)OG</a></p>
        <p class="mb-2">趣味：写真</p>
        <p class="mb-2">技術：<br>HTML / CSS / C / Python / Flutter / Git /<br>JavaScript( Node / Vue / React / Next )</p>
        <a href="https://github.com/shu00011" target="_blank" rel="noopener noreferrer">
          <MyButton text="GitHubはこちら"></MyButton>
        </a>
        <div class="my-2"></div>
        <a href="https://zenn.dev/shu00011" target="_blank" rel="noopener noreferrer">
          <MyButton text="Zennはこちら"></MyButton>
        </a>
      </div>
    </div>
</template>

<script>
import MyButton from "~/components/MyButton"

export default {
  data: function () {
    return {
      name: 'profile',
    }
  },
  components:{
    MyButton
  },
}
</script>

<style scoped>
h2{
  font-family:'Kiwi Maru',serif;
}

.myimg{
  border-radius:10% 10% 28% 72% / 10% 10% 80% 51% ;
}
</style>
