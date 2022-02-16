<template>
  <div>
    <div class="grid grid-col-12">
      <div class="text-gray-700 text-2xl grid md:col-start-5 md:col-end-6 z-20 left-8 top-5 absolute">
        <router-link to="/" class="mb-4">top</router-link>
        <router-link to="/profile">about</router-link>
      </div>
    </div>
    <h2 class="absolute right-8 top-5 text-gray-400 text-4xl">works</h2>
    <div>
      <div class="text-gray-700">
        <div class="rounded-lg border-2 border-gray-600 mb-10 p-10 pb-15">
          <img src="~/assets/twitter.png" alt="twitter_timeline_mdeia" class="rounded-t-lg" />
          <p class="mb-2 mt-2">名前：twitter_time_line_media</p>
          <p class="mb-2">開発：個人開発</p>
          <p class="mb-2">技術：Python</p>
          <p class="mb-2">説明：twitterのタイムライン上にある最新の画像を，streamlitを使用しローカルホスト上で表示．</p>
          <a class="border-2 border-gray-600 bg-white text-gray-600 text-xs py-2 px-4 w-40 h-38 rounded-full tracking-widest hover:bg-gray-600 hover:text-white" href="https://oucrc.net/articles/okp0bbco4s" target="_blank" rel="noopener noreferrer">oucrcの記事はこちら</a>
        </div>
        <div class="rounded-lg border-2 border-gray-600 mb-10 p-10 pb-15">
          <img src="~/assets/nuxt.PNG" alt="nuxt" class="rounded-t-lg" />
          <p class="mb-2 mt-2">名前：Nuxt.js+Netlifyを使用したWebサイト構築</p>
          <p class="mb-2">開発：個人開発</p>
          <p class="mb-2">技術：Nuxt.js</p>
          <p class="mb-2">説明：本Webサイトを構築．</p>
          <a class="border-2 border-gray-600 bg-white text-gray-600 text-xs py-2 px-4 w-40 h-38 rounded-full tracking-widest hover:bg-gray-600 hover:text-white" href="https://oucrc.net/articles/5epogqmu2lk" target="_blank" rel="noopener noreferrer">oucrcの記事はこちら</a>
        </div>
        <div class="rounded-lg border-2 border-gray-600 mb-10 p-10 pb-15">
          <img src="~/assets/cacao.PNG" alt="cacao" class="rounded-t-lg" />
          <p class="mb-2 mt-2">名前：cacao</p>
          <p class="mb-2">開発：チーム開発(フロントエンド担当)</p>
          <p class="mb-2">技術：Flutter</p>
          <p class="mb-2">説明：学生証をかざすことで学生を識別し，体温の記録を行うAndroid/iOSアプリ．新型コロナウイルスの感染拡大防止目的に制作．</p>
          <a class="border-2 border-gray-600 bg-white text-gray-600 text-xs py-2 px-4 w-40 h-38 rounded-full tracking-widest hover:bg-gray-600 hover:text-white" href="https://apps.apple.com/jp/app/cacao/id1577030127" target="_blank" rel="noopener noreferrer">アプリのダウンロードはこちら</a>
        </div>
        <div class="rounded-lg border-2 border-gray-600 mb-10 p-10 pb-15">
          <img src="~/assets/fes.PNG" alt="2021oufes" class="rounded-t-lg" />
          <p class="mb-2 mt-2">名前：2021年度岡山大学オンライン大学祭</p>
          <p class="mb-2">開発：チーム開発（書道部のピックアップページを担当）</p>
          <p class="mb-2">技術：Nuxt.js</p>
          <p class="mb-2">説明：2021年度の岡山大学オンライン大学祭を電子計算機研究会で制作．</p>
          <a class="border-2 border-gray-600 bg-white text-gray-600 text-xs py-2 px-4 w-40 h-38 rounded-full tracking-widest hover:bg-gray-600 hover:text-white" href="https://github.com/oucrc-org/okayama-univ-fes-2021" target="_blank" rel="noopener noreferrer">GitHubのリポジトリはこちら</a>
        </div>
        <div class="rounded-lg border-2 border-gray-600 mb-10 p-10 pb-15">
          <img src="~/assets/help_b.png" alt="shisakubot" class="rounded-t-lg" />
          <p class="mb-2 mt-2">名前：試作bot</p>
          <p class="mb-2">開発：個人開発</p>
          <p class="mb-2">技術：Python</p>
          <p class="mb-2">説明：Pythonを使って動くものがつくってみたくなり，初めて制作したDiscord bot．</p>
          <a class="border-2 border-gray-600 bg-white text-gray-600 text-xs py-2 px-4 w-40 h-38 rounded-full tracking-widest hover:bg-gray-600 hover:text-white" href="https://github.com/shu00011/Shisaku_discord_bot" target="_blank" rel="noopener noreferrer">GitHubのリポジトリはこちら</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      name: 'works',
    }
  },

}
</script>

<style scoped>
h2{
  font-family:'Kiwi Maru',serif;
}
</style>
