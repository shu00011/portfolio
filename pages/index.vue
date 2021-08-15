<template>
<!--  <Tutorial/>-->
  <div :style="{height:height+'px'}" class="backImage">
    <div :style="{height:height+'px'}" class="absolute">
      <Header/>
      <p>{{title}}</p>
      <hello-world message='This is a message.'/>
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
  }
}
</script>

<style>
.backImage{
  /*background-image:radial-gradient(ellipse at center,rgba(189,195,199,0.1) 50%, rgba(44,62,80,0.5) 100%), url(~static/monoF.jpg);*/
  /*background-image:radial-gradient(ellipse at center,rgba(189,195,199,0.1) 50%, rgba(44,62,80,0.5) 100%), url(~static/ship.jpg);*/
  /*background-image:rgba(245,245,245,0.1),url(~static/shipLY.jpg);*/
  background-image:url(~static/shipLY.jpg);
  background-size:1800px;
  position:relative;
}
.absolute{
  position:absolute;
  background-color:rgba(245,245,245,0.3);
  width:100%;
  /*width:1450px;*/
  /*height:750px;*/
}
</style>
