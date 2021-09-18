<template>
  <div class="all">
    <div class="side">
      <Sidemenu/>
    </div>
    <div class="head visible sm:invisible">
      <Header/>
    </div>
    <div class="workscontents">
      <div class="menu">
        <h1>works</h1>
        <hr>
        <table>
          <tr>
            <th>twitter_timeline_media:</th>
            <th>Python</th>
          </tr>
          <tr>
            <th>試作bot：</th>
            <th>Python</th>
          </tr>
          <tr>
            <th>cacao：</th>
            <th>Flutter</th>
          </tr>
        </table>
      </div>
      <div class="twitter">
        <div class="title">
          <a href="https://github.com/shu00011/twitter_timeline_media" target="_blank" rel="noopener noreferrer">
            <h1>twitter_timeline_media</h1>
          </a>
        </div>
        <hr>
        <div class="sentence">
          <table>
            <tr>
              <th>名前：</th>
              <th>twitter_timeline_media</th>
            </tr>
            <tr>
              <th>開発：</th>
              <th>個人開発</th>
            </tr>
            <tr>
              <th>技術：</th>
              <th>Python</th>
            </tr>
            <tr>
              <th>説明：</th>
              <th>twitterのタイムライン上にある最新の画像を，streamlitを使用しローカルweb上で表示します．詳しいことはこちらの<a
                href="https://oucrc.net/articles/okp0bbco4s" target="_blank" rel="noopener noreferrer">記事</a>にあります．
              </th>
            </tr>
          </table>
        </div>
      </div>
      <div class="discordbot">
        <div class="title">
          <a href="https://github.com/shu00011/Shisaku_discord_bot" target="_blank" rel="noopener noreferrer">
            <h1>試作bot</h1>
          </a>
        </div>
        <hr>
        <div class="sentence">
          <table>
            <tr>
              <th>名前：</th>
              <th>試作bot</th>
            </tr>
            <tr>
              <th>開発：</th>
              <th>個人開発</th>
            </tr>
            <tr>
              <th>技術：</th>
              <th>Python</th>
            </tr>
            <tr>
              <th>説明：</th>
              <th>Pythonを使って動くものを作ってみたくなり，Discord botを制作しました．画像は実装した機能です．</th>
            </tr>
          </table>
        </div>
        <div class="botImage">
          <img src="~/assets/help_b.png" alt="Discord botで実装した機能一覧"/>
        </div>
      </div>
      <div class="cacao">
        <div class="title">
          <a href="https://apps.apple.com/jp/app/cacao/id1577030127" target="_blank" rel="noopener noreferrer">
            <h1>cacao</h1>
          </a>
        </div>
        <hr>
        <div class="sentence">
          <table>
            <tr>
              <th>名前：</th>
              <th>cacao</th>
            </tr>
            <tr>
              <th>開発：</th>
              <th>チーム開発（Flutterによるフロントエンド実装を担当）</th>
            </tr>
            <tr>
              <th>技術：</th>
              <th>Flutter</th>
            </tr>
            <tr>
              <th>説明：</th>
              <th>学生証をかざすことで学生を識別し，体温の記録を行うAndroid/iOSアプリです．新型コロナウイルスの感染拡大防止を目的に作られました．画像は担当したUIの制作画面です．</th>
            </tr>
          </table>
        </div>
        <div class="cacaoImage">
          <img src="~/assets/cacao.PNG" alt="cacaoで担当したUIの制作画面"/>
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
.all {
  position: relative;
  width:100%;
}

.side {
  position: absolute;
}



.workscontents {
  top: 110px;
  position: absolute;
  color: #f5f5f5;
  padding: 40px 30px 0 30px;
  background-color: #2B9999;
  max-width:100%;
}

.title {
  font-family: 'Geo', sans-serif;
}

.twitter {
  padding-top: 20px;
}

.discordbot {
  padding-top: 20px;
}

.botImage {
  padding-top: 10px;
}

.cacao {
  padding-top: 20px;
}

.cacaoImage {
  padding: 10px;
}

h1 {
  font-family: 'Geo', sans-serif;
  color: #f5f5f5;
  font-size: 30px;
}

th {
  font-weight: lighter;
  text-align: left;
  font-family: 'Shippori Mincho', serif;
}

.sentence a {
  color: #00cde1;
}

@media (min-width: 640px) {
  .all {
    background-color: #f5f5f5;
    height: 2000px;
    width: 100%;
  }

  .workscontents {
    top: 100px;
    left: 320px;
  }

  .title:hover {
    opacity: 0.8;
    letter-spacing: 5px;
  }

  .sentence a:hover {
    opacity: 0.8;
    letter-spacing: 5px;
  }

  a {
    text-decoration: none;
    color: #2f2f2f;
  }

  th {
    font-weight: lighter;
    text-align: left;
    font-family: 'Shippori Mincho', serif;
  }
}
</style>
