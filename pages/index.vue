<template>
  <!--  <Tutorial/>-->
  <div class="back">
    <div class="side">
      <Sidemenu/>
      <div class="image"></div>
    </div>
    <div class="head">
      <Header/>
    </div>
    <div class="phone">
        <h1>shu00011 portfolio</h1>
    </div>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      title: 'Hello, World!!',
    }
  },
}
</script>

<style>
.back {
  position: relative;
  background-color:#f5f5f5;
  width:100%;
}

.side {
  position: absolute;
}

.head {
  position: absolute;
  width:100%;
}

.phone{
  position:absolute;
  top:200px;
  left:100px;
  font-family: 'Shippori Mincho', serif;
  color:#a9a9a9;
}

@media (min-width: 640px) {

  .image {
    position: absolute;
    height: 783px;
    background-image: url('~/assets/my.png');
    width: 1174px;
    top: 80px;
    left: 245px;
  }

  .phone{
    color:rgba(245,245,245,0);
    top:0;
    left:500px;
    cursor: default;
  }

  h1 {
    padding-left: 30px;
    font-weight: lighter;
  }

  ul {
    list-style: none;
    padding-top: 170px;
    padding-right: 68px;
    text-align: right;
  }

  li {
    padding: 15px;
    font-size: 25px;
    font-family: 'Geo', sans-serif;
  }

  a {
    text-decoration: none;
    color: #f5f5f5;
  }

  h1:hover {
    opacity: 0.8;
  }

  li:hover {
    letter-spacing: 5px;
    opacity: 0.8;
  }
}
</style>
