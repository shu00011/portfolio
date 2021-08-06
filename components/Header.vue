<template>
  <header>
    <div class="header_flex">
  <!-- データを表示させる-->
      <h1>{{title}}</h1>
      <nav>
        <ul>
          <li>profile</li>
          <li>works</li>
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
    background-color: #f5f5f5;
    text-align:center;
    padding:10px;
    font-family:'Geo', sans-serif;
    font-weight: lighter;
  }
  h1{
    color: #a9a9a9;
    margin:0;
    font-family:'Geo', sans-serif;
    font-weight: lighter;
  }
  p{
    color:#000;
    margin:0;
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
