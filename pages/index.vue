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
  background-color: #f5f5f5;
}

.side {
  position: absolute;
}

.head {
  position: absolute;
}

.image {
  position: absolute;
  width: 840px;
  height: 783px;
  top: 0;
  left: -200px;
  background-image: url('~/assets/my.png');
}

@media (min-width: 640px) {
  .image {
    width: 1174px;
    top: 80px;
    left: 245px;
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
