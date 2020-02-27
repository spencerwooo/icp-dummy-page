<template>
  <div class="about">
    <img alt="under construction" src="@/assets/work.png" width="36px" height="36px" />
    <div class="icp">
      <span class="construction" id="title-pink">阿里雲</span>
      <span class="construction">這就是老子的備案頁面</span>
      <span class="construction" id="title-pink"> Mic Drop!</span>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'about',
  components: {}
}
</script>

<style scoped>
.about {
  height: 20vh;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: flex-start;
  align-items: center;
  align-content: stretch;
}

h1 {
  margin: 0 0;
}

.icp {
  margin: 10px 0 0 10px;
  font-weight: bold;
  color: #ffffff;
}

.icp a {
  color: #eae7af;
  font-weight: bold;
}

@media only screen and (max-width: 700px) {
  .about {
    height: 15vh;
  }

  .icp {
    font-size: 0.9rem;
  }
}

@media only screen and (min-width: 700px) and (max-width: 1000px) {
  .about {
    height: 12vh;
  }
}
</style>
