<template>
  <div class="home">
    <img alt="under construction" src="@/assets/construction.png" width="36px" height="36px" />
    <div class="icp">
      <span class="construction" id="title-pink">是的是的是的</span>
      <span class="construction">我正在被開發</span>
      <span class="construction" id="title-pink">
        來看看我閃亮亮的
        <a href="http://www.beian.miit.gov.cn">京 ICP 備 {{ icp }}</a>
      </span>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {},
  data () {
    return {
      icp: process.env.VUE_APP_ICP ? process.env.VUE_APP_ICP : ''
    }
  },
  mounted () {
    console.log('ICP:', process.env.VUE_APP_ICP)
  }
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
  .home {
    height: 15vh;
  }

  .icp {
    font-size: 0.9rem;
  }
}

@media only screen and (min-width: 700px) and (max-width: 1000px) {
  .home {
    height: 12vh;
  }
}
</style>
