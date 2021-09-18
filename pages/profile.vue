<template>
  <div class="back">
    <div class="side">
      <Sidemenu/>
      <div class="image"></div>
    </div>
    <div class="head">
      <Header/>
    </div>
    <div class="content">
      <table>
        <tr>
          <th>名前：</th>
          <th>shu00011<div class="toHover"><a href="https://oucrc.net/members/9svd4hgoy" target="_blank" rel="noopener noreferrer">小石こは(電子計算機研究会)</a></div></th>
        </tr>
        <tr>
          <th>所属：</th>
          <th>岡山大学工学部情報系学科3年</th>
        </tr>
        <tr>
          <th>趣味：</th>
          <th>写真</th>
        </tr>
        <tr>
          <th>技術：</th>
          <th>
            <div class="skills">
              <div class="skill">HTML</div>
              <div class="skill">CSS</div>
              <div class="skill">JavaScript</div>
              <div class="skill">Node.js</div>
              <div class="skill">Vue.js</div>
              <a href="https://oucrc.net/articles/5epogqmu2lk" target="_blank" rel="noopener noreferrer">
                <div class="skill toHover">Nuxt.js</div>
              </a>
            </div>
            <div class="skills">
              <div class="skill">C</div>
              <router-link class="nav-link" to="/works">
                <div class="skill toHover">Python</div>
              </router-link>
              <router-link class="nav-link" to="/works">
                <div class="skill toHover">Flutter</div>
              </router-link>
              <a href="https://github.com/shu00011" target="_blank" rel="noopener noreferrer">
                <div class="skill toHover">Git</div>
              </a>
            </div>
          </th>
        </tr>
      </table>
    </div>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      name: 'profile',
    }
  }
}
</script>

<style scoped>
.back {
  position: relative;
  width:100%;
}

.head {
  position: absolute;
  width:100%;
}

.content {
  position: absolute;
  top: 100px;
  left: 100px;
}

.side {
  position: absolute;
}

.content {
  font-family: 'Shippori Mincho', serif;
  position: absolute;
  top: 150px;
  left: 30px;
  text-align: center;
  color: #f5f5f5;
  background-color: rgba(46, 139, 87, 0.7);
}

.toHover{
  color: #00cde1;
}

.toHover a{
  color: #00cde1;
}

.skills {
  font-family: 'Geo', sans-serif;
  font-size: 20px;
  color: #f5f5f5;
  margin: 10px;
}

th {
  font-weight: lighter;
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

  .content {
    left: 350px;
  }

  .skills {
    font-size: 15px;
    display: flex;
  }

  .skill {
    width: 80px;
    padding: 3px;
  }

  th {
    text-align: left;
  }

  a {
    text-decoration: none;
    color: #f5f5f5;
  }

  .toHover:hover {
    opacity: 0.5;
    letter-spacing: 5px;
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
