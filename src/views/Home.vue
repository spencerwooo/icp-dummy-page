<template>
  <div class="home">
    <img alt="under construction" src="@/assets/construction.png" width="36px" height="36px" />
    <div class="icp">
      <span class="construction" id="title1">是的是的是的我正在被開發</span>
      <span class="construction">這你難道看不出來嗎那你是真的很機車耶</span>
      <span class="construction" id="title1">
        來看看我閃亮亮的
        <a href="http://www.beian.miit.gov.cn">京 ICP 備 17065315</a>
      </span>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {}
}
</script>

<style scoped>
.home {
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
</style>
