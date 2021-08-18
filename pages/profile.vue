<template>
  <div>
    <Sidemenu/>
    <div class="image"></div>
    <div class="content">
      <table>
        <tr>
          <th>名前：</th>
          <th>shu00011（しゅう）</th>
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
              <div class="skill">Nuxt.js</div>
            </div>
            <div class="skills">
              <div class="skill">C</div>
              <router-link class="nav-link" to="/works">
                <div class="skill toHover">Python</div>
              </router-link>
              <router-link class="nav-link" to="/works">
                <div class="skill toHover">Flutter</div>
              </router-link>
              <a href="https://github.com/shu00011" target="_blank" rel="noopener noreferrer"><div class="skill toHover">Git</div></a>
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
.image{
  position:absolute;
  background-color:#000000;
  width:1174px;
  height:783px;
  top:80px;
  left:245px;
  background-image:url('~assets/my.png');
}
.content{
  font-family: 'Shippori Mincho', serif;
  position:absolute;
  top:180px;
  left:350px;
  text-align:center;
  color:#f5f5f5;
  background-color:rgba(46,139,87,0.7);
}
.skills{
  font-family:'Geo', sans-serif;
  font-size:15px;
  color:#f5f5f5;
  margin:10px;
  display:flex;
}
.skill{
  width:80px;
  border-radius:5px;
  padding:3px;
}
th{
  font-weight:lighter;
  text-align:left;
}
a{
  text-decoration:none;
  color:#f5f5f5;
}
.toHover:hover{
  opacity:0.5;
  letter-spacing:5px;
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
