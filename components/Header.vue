<template>
  <header>
    <div class="header_flex">
  <!-- データを表示させる-->
        <div class="title">
          <router-link class="nav-link topIcon hoverDesign" to="/">
            <img src="~static/logoNSM.png">
          </router-link>
        </div>
      <nav>
        <ul>
          <li>
            <router-link class="nav-link menu hoverDesign" to="/profile">PROFILE</router-link>
          </li>
          <li>
            <router-link class="nav-link menu hoverDesign" to="/works">WORKS</router-link>
          </li>
        </ul>
      </nav>
      <!--<p>{{subTitle}}</p>-->
    </div>
  </header>
</template>

<script>
export default {
  data(){
    return{
      title:"shu00011",
      //subTitle:"portfolio"
    }
  },
  name: "Header"
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Geo&display=swap');
  header{
    background-color: rgba(245,245,245,0.1);
    text-align:center;
    padding:10px;
    font-family:'Geo', sans-serif;
    font-weight: lighter;
  }
  .title{
    top:0;
    left:0;
    position:absolute;
  }
  .menu{
    color:#44a49c;
  }
  .hoverDesign:hover{
    /* font-size:98%; */
    letter-spacing:5px;
    opacity:0.8;
  }
  p{
    color:#000;
    margin:0;
  }
  a{
    text-decoration:none;
    font-size:20px;
  }
  ul{
    list-style:none;
  }
  div{
    padding:0 30px;
  }
  .header_flex{
    display:flex;
    height:90px;
    align-items:center;
    position:relative;
  }
  .header_flex nav{
   margin-left:60px;
  }
  .header_flex ul{
    display:flex;
  }
  .header_flex ul li{
    margin-left:20px;
  }
</style>
