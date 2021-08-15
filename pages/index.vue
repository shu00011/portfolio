<template>
<!--  <Tutorial/>-->
  <div :style="{height:height+'px'}" class="back">
    <div class="menu">
      <router-link class="nav-link" to="/">
        <div class="title">
          <img src="~static/logoN.png">
        </div>
      </router-link>
      <ul>
        <li>
          <router-link class="nav-link" to="/profile">PROFILE</router-link>
        </li>
        <li>
          <router-link class="nav-link" to="/works">WORKS</router-link>
        </li>
      </ul>
      <div class="github">
        <a href="https://github.com/shu00011">
          <i class="fab fa-github-square fa-2x">
          </i>
        </a>
      </div>
      <div class="image">

      </div>
    </div>
  </div>
</template>

<script>
import HelloWorld from "~/components/HelloWorld";
import Header from "~/components/Header";
export default {
  data:function(){
    return{
      title:'Hello, World!!',
      height:0,
    }
  },
  created(){  // イベントリスナーを追加．resize（画面サイズが変わる）度にhandleResize()メソッドを呼び出す．
    if(process.client){
      window.addEventListener('resize',this.handleResize)
      this.handleResize()
    }
  },
  destroyed(){
    if(process.client){
      window.removeEventListener('resize',this.handleResize)
    }
  },
  methods:{
    handleResize(){ // windowの高さを取得するメソッド
      this.height=window.innerHeight
    }
  },
  components:{
    Header,
    HelloWorld
  },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Geo&display&family=Josefin+Sans:ital,wght@1,200&display=swap');
.back{
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
.image{
  position:absolute;
  background-color:#000000;
  width:1174px;
  height:783px;
  top:80px;
  left:180px;
  background-image:url(~static/my.png);
}
.title{
  width:20px;
  height:20px;
}
.github{
  padding-top:210px;
  padding-left:125px;
  width:50px;
  color:#f5f5f5;
}
h1{
  padding-left:30px;
  font-weight:lighter;
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
