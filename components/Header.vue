<template>
  <header>
    <div class="header_flex">
  <!-- データを表示させる-->
        <h1>
          <router-link class="nav-link topIcon hoverDesign" to="/">{{title}}</router-link>
        </h1>
      <nav>
        <ul>
          <li>
            <router-link class="nav-link menu hoverDesign" to="/profile">profile</router-link>
          </li>
          <li>
            <router-link class="nav-link menu hoverDesign" to="/works">works</router-link>
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
    background-color: rgba(245,245,245,0);
    text-align:center;
    padding:10px;
    font-family:'Geo', sans-serif;
    font-weight: lighter;
  }
  h1{
    margin:0;
    font-family:'Geo', sans-serif;
    font-weight: lighter;
  }
  .topIcon{
    color:#a9a9a9;
  }
  .menu{
    color:#f5f5f5;
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
  }
  ul{
    list-style:none;
  }
  div{
    padding:0 30px;
  }
  .header_flex{
    display:flex;
    height:60px;
    align-items:center;
  }
  .header_flex nav{
    margin-left:auto;
  }
  .header_flex ul{
    display:flex;
  }
  .header_flex ul li{
    margin-left:20px;
  }
</style>
