<template>
  <div>
    <div class="grid grid-col-12">
      <div class="text-gray-700 text-2xl grid md:col-start-5 md:col-end-6 z-20 left-8 top-5 absolute">
        <router-link to="/" class="mb-4">top</router-link>
        <router-link to="/profile">about</router-link>
      </div>
    </div>
    <h2 class="absolute right-8 top-8 text-gray-400 text-4xl">works</h2>
    <div class="mt-32">
      <div class="text-gray-700">
        <div class="rounded-lg border-2 border-gray-600 mb-10 p-10 pb-15">
          <img src="~/assets/streamlit.PNG" alt="2021oufes" class="rounded-t-lg" />
          <p class="mb-2 mt-2">名前：rbsc_streamlit_prototype</p>
          <p class="mb-2">制作日：2022/07/27</p>
          <p class="mb-2">開発：個人</p>
          <p class="mb-2">技術：Python</p>
          <p class="mb-2">説明：RBSCアルゴリズムをWebアプリケーション上で利用できるようにしたもの．</p>
          <a class="border-2 border-gray-600 bg-white text-gray-600 text-xs py-2 px-4 w-40 h-38 rounded-full tracking-widest hover:bg-gray-600 hover:text-white" href="https://shu00011-rbsc-streamlit-prototype-main-npqgvz.streamlitapp.com/" target="_blank" rel="noopener noreferrer">Webアプリはこちら</a>
        </div>
        <div class="rounded-lg border-2 border-gray-600 mb-10 p-10 pb-15">
          <img src="~/assets/club.PNG" alt="2022clubfes" class="rounded-t-lg" />
          <p class="mb-2 mt-2">名前：2022年度岡山大学部活動フェスティバル</p>
          <p class="mb-2">制作日：2022/04/01</p>
          <p class="mb-2">開発：チーム（複数のパーツを担当）</p>
          <p class="mb-2">技術：Next.js</p>
          <p class="mb-2">説明：2022年度の岡山大学部活動フェスティバルを電子計算機研究会で制作．</p>
        </div>
        <div class="rounded-lg border-2 border-gray-600 mb-10 p-10 pb-15">
          <img src="~/assets/fes.PNG" alt="2021oufes" class="rounded-t-lg" />
          <p class="mb-2 mt-2">名前：2021年度岡山大学オンライン大学祭</p>
          <p class="mb-2">制作日：2021/11/21</p>
          <p class="mb-2">開発：チーム（書道部のピックアップページを担当）</p>
          <p class="mb-2">技術：Nuxt.js</p>
          <p class="mb-2">説明：2021年度の岡山大学オンライン大学祭を電子計算機研究会で制作．</p>
          <a class="border-2 border-gray-600 bg-white text-gray-600 text-xs py-2 px-4 w-40 h-38 rounded-full tracking-widest hover:bg-gray-600 hover:text-white" href="https://github.com/oucrc-org/okayama-univ-fes-2021" target="_blank" rel="noopener noreferrer">GitHubのリポジトリはこちら</a>
        </div>
        <div class="rounded-lg border-2 border-gray-600 mb-10 p-10 pb-15">
          <img src="~/assets/nuxt.PNG" alt="nuxt" class="rounded-t-lg" />
          <p class="mb-2 mt-2">名前：Nuxt.js+Netlifyを使用したWebサイト構築</p>
          <p class="mb-2">制作日：2021/09/18</p>
          <p class="mb-2">開発：個人</p>
          <p class="mb-2">技術：Nuxt.js</p>
          <p class="mb-2">説明：本Webサイトを構築．</p>
          <a class="border-2 border-gray-600 bg-white text-gray-600 text-xs py-2 px-4 w-40 h-38 rounded-full tracking-widest hover:bg-gray-600 hover:text-white" href="https://zenn.dev/shu00011/articles/0e5937ca1ff85b" target="_blank" rel="noopener noreferrer">Zennの記事はこちら</a>
        </div>
        <div class="rounded-lg border-2 border-gray-600 mb-10 p-10 pb-15">
          <img src="~/assets/twitter.png" alt="twitter_timeline_mdeia" class="rounded-t-lg" />
          <p class="mb-2 mt-2">名前：twitter_timeline_media</p>
          <p class="mb-2">制作日：2021/08/23</p>
          <p class="mb-2">開発：個人</p>
          <p class="mb-2">技術：Python</p>
          <p class="mb-2">説明：twitterのタイムライン上にある最新の画像を，ローカルホスト上でstreanlitを使用して表示．</p>
          <a class="border-2 border-gray-600 bg-white text-gray-600 text-xs py-2 px-4 w-40 h-38 rounded-full tracking-widest hover:bg-gray-600 hover:text-white" href="https://zenn.dev/shu00011/articles/9392ef6aa56c7f" target="_blank" rel="noopener noreferrer">Zennの記事はこちら</a>
        </div>
        <div class="rounded-lg border-2 border-gray-600 mb-10 p-10 pb-15">
          <img src="~/assets/cacao.PNG" alt="cacao" class="rounded-t-lg" />
          <p class="mb-2 mt-2">名前：cacao</p>
          <p class="mb-2">制作日：2021/07/23</p>
          <p class="mb-2">開発：チーム(複数の画面を担当)</p>
          <p class="mb-2">技術：Flutter</p>
          <p class="mb-2">説明：学生証をかざすことで学生を識別し，体温の記録を行うAndroid/iOSアプリ．新型コロナウイルスの感染拡大防止が目的．</p>
          <a class="border-2 border-gray-600 bg-white text-gray-600 text-xs py-2 px-4 w-40 h-38 rounded-full tracking-widest hover:bg-gray-600 hover:text-white" href="https://apps.apple.com/jp/app/cacao/id1577030127" target="_blank" rel="noopener noreferrer">アプリのインストールはこちら</a>
        </div>
        <div class="rounded-lg border-2 border-gray-600 mb-10 p-10 pb-15">
          <img src="~/assets/help_b.png" alt="shisakubot" class="rounded-t-lg" />
          <p class="mb-2 mt-2">名前：試作bot</p>
          <p class="mb-2">制作日：2021/06/06</p>
          <p class="mb-2">開発：個人</p>
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
