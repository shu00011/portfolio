<template>
  <div :style="{height:height+'px'}" class="back">
    <div class="menu">
      <router-link class="nav-link" to="/">
        <div class="title">
          <img src="~/assets/logoN.png" alt="ロゴ"/>
        </div>
      </router-link>
      <ul>
        <li>
          <!--<div class="container">
            <ModalProfile v-on:componentAlert="Alert" />
          </div>-->
          <router-link class="nav-link" to="/profile">PROFILE</router-link>
        </li>
        <li>
          <router-link class="nav-link" to="/works">WORKS</router-link>
        </li>
      </ul>
      <div class="github">
        <a href="https://github.com/shu00011" target="_blank" rel="noopener noreferrer">
          <i class="fab fa-github-square fa-2x">
          </i>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      name: 'Sidemenu',
      height: 0,
    }
  },
  created() {  // イベントリスナーを追加．resize（画面サイズが変わる）度にhandleResize()メソッドを呼び出す．
    if (process.client) {
      window.addEventListener('resize', this.handleResize)
      this.handleResize()
    }
  },
  destroyed() {
    if (process.client) {
      window.removeEventListener('resize', this.handleResize)
    }
  },
  methods: {
    handleResize() { // windowの高さを取得するメソッド
      this.height = window.innerHeight
    }
  }
}
</script>

<style scoped>
.back{
  font-family: 'Shippori Mincho', serif;
  position:relative;
  background-color:#f5f5f5;
}

.menu{
  position:absolute;
  background-color:#2e8b57;
  width:230px;
  height:640px;
  left:65px;
}
.title{
  width:20px;
  height:20px;
}
.github{
  padding-top:210px;
  padding-left:120px;
  width:50px;
  color:#f5f5f5;
}
ul{
  list-style:none;
  padding-top:170px;
  padding-right:68px;
  text-align:right;
}
li{
  padding:15px;
  font-size:25px;
  font-family:'Geo', sans-serif;
}
a{
  text-decoration:none;
  color:#f5f5f5;
}
h1:hover{
  opacity:0.8;
}
li:hover{
  letter-spacing:5px;
  opacity:0.8;
}
.github:hover{
  opacity:0.8;
}
</style>
