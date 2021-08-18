<template>
  <div class="all">
    <Sidemenu/>
    <div class="contents">
      <div class="menu">
        <h1>works</h1>
        <hr>
        <table>
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
          <img src="~/static/help_b.png">
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
          <img src="~/static/cacao.png">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Sidemenu from "~/components/Sidemenu";
export default {
  data: function () {
    return {
      name: 'works',
    }
  },

}
</script>

<style scoped>
.all{
  position:relative;
  background-color:#f5f5f5;
  height:1850px;
  width:1450px;
}
.contents{
  position:absolute;
  top:10px;
  left:320px;
}
.title{
  font-family:'Geo', sans-serif;
}
.discordbot{
  padding-top:20px;
}
.botImage{
  padding-top:10px;
}
.cacao{
  padding-top:20px;
}
.cacaoImage{
  padding:10px;
}
.title:hover{
  opacity:0.8;
  letter-spacing:5px;
}
a{
  text-decoration:none;
  color:#2f2f2f;
}
th{
  font-weight:lighter;
  text-align:left;
  font-family: 'Shippori Mincho', serif;
}
h1{
  font-family:'Geo', sans-serif;
  color:#2f2f2f;
}
</style>
