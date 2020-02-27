<template>
  <div class="about">
    <img alt="under construction" src="@/assets/work.png" width="36px" height="36px" />
    <div class="icp">
      <span class="construction" id="title1">阿里雲</span>
      <span class="construction">這就是老子的備案頁面</span>
      <span class="construction" id="title1"> Mic Drop!</span>
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
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: start;
  align-items: stretch;
  align-content: stretch;
  padding: 50px 0;
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
</style>
