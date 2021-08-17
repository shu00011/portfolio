<template>
<!--  <Tutorial/>-->
  <div>
    <Sidemenu/>
      <div class="image">
      </div>
  </div>
</template>

<script>
export default {
  data:function(){
    return{
      title:'Hello, World!!',
    }
  },
}
</script>

<style>
.image{
  position:absolute;
  background-color:#000000;
  width:1174px;
  height:783px;
  top:80px;
  left:245px;
  background-image:url(~static/my.png);
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
</style>
