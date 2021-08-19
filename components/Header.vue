<template>
  <div class="back header_flex visible sm:invisible">
    <!-- データを表示させる-->
    <div class="title">
      <router-link class="nav-link topIcon" to="/">
        <img src="~static/logoNSM.png" alt="header用のロゴ"/>
      </router-link>
    </div>
    <nav>
      <ul>
        <li>
          <router-link class="nav-link menu" to="/profile">PROFILE</router-link>
        </li>
        <li>
          <router-link class="nav-link menu" to="/works">WORKS</router-link>
        </li>
        <li>
          <div class="github">
            <a href="https://github.com/shu00011" target="_blank" rel="noopener noreferrer">
              <i class="fab fa-github-square fa-2x">
              </i>
            </a>
          </div>
        </li>
      </ul>
    </nav>
    <!--<p>{{subTitle}}</p>-->
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "shu00011",
      //subTitle:"portfolio"
    }
  },
  name: "Header"
}
</script>

<style scoped>
.back {
  background-color: rgba(245, 245, 245, 0.1);
  text-align: center;
  padding: 10px;
  font-family: 'Geo', sans-serif;
  font-weight: lighter;
}

.title {
  top: 0;
  left: 0;
  position: absolute;
}

.menu {
  color: #44a49c;
}

.github {
  color: #f5f5f5;
  position: absolute;
  left: 290px;
}

p {
  color: #000;
  margin: 0;
}

a {
  text-decoration: none;
  font-size: 20px;
}

ul {
  list-style: none;
}

div {
  padding: 0 30px;
}

.header_flex {
  display: flex;
  height: 100px;
  width: 640px;
  align-items: center;
  position: relative;
}

.header_flex nav {
  margin-left: 140px;
}

.header_flex ul {
  display: flex;
}

.header_flex ul li {
  margin-left: 15px;
}
</style>
