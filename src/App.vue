<template>
  <div id="app">
    <div id="top-box">
      <div id="nav">
        <span id="title1" class="header">信息高速公路</span>
        <span id="title2" class="header">暢通無阻全球資訊網</span>
        <span id="title3" class="header">萬物互聯</span>
        <span id="title4" class="header">因特網内容提供服務中國互聯網</span>
        <span id="title5" class="header">服務供應</span>
        <span id="title6" class="header">贊大佬</span>
        <span id="title7" class="header">實在太强了</span>

        <div id="router-links">
          <router-link to="/">主頁</router-link> |
          <router-link to="/about">爲什麽設置這個頁面</router-link>
        </div>
      </div>
    </div>
    <div id="bottom-box">
      <router-view />
    </div>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css?family=Rubik&display=swap");

body {
  padding: 0px 0px;
  margin: 0px 0px;
  background: #32547b;
  height: 100%;
}

#app {
  font-family: Rubik, Helvetica, Arial, Noto Sans CJK SC, Sarasa Gothic SC,
    Microsoft YaHei, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #ffffff;
}

#top-box {
  width: 100%;
  background: #154165;
}

#nav {
  max-width: 900px;
  margin: 0px auto;
  padding: 100px 10px;
}

#nav a {
  font-weight: bold;
  color: #ffffff;
}

#nav a.router-link-exact-active {
  color: #eae7af;
}

.header {
  font-family: Nova Mono, Helvetica, Arial, Noto Sans CJK SC, Sarasa Gothic SC,
    Microsoft YaHei, sans-serif;
  font-weight: bold;
  font-size: 3.7rem;
  color: rgba(255, 255, 255, 0.5);
}

#title1 {
  color: #eab0d9;
}

#title4 {
  color: #eae7af;
}

#title6 {
  color: #d65a31;
}

#router-links {
  margin-top: 2rem;
}

#bottom-box {
  max-width: 900px;
  margin: 0px auto;
  padding: 30px;
}
</style>
