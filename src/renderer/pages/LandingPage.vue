<template>
  <div class="landing-page">
    <div class="login-wrapper">
      <input-component></input-component>
    </div>
    <div class="news-wrapper">新闻信息页</div>
  </div>
</template>
<script>
import InputComponent from "@/components/input/input"

export default {
  data() {
    return {};
  },
  components: {
    InputComponent
  }
};
</script>

<style lang="scss" scoped>
.landing-page {
  position: absolute;
  width: 100%;
  height: 100%;
  left: 0px;
  top: 0px;
  overflow: hidden;
  .login-wrapper {
    width: 30%;
    height: 100%;
    background: red;
    float: left;
  }
  .news-wrapper{
    width: 70%;
    height: 100%;
    background: blue;
    float: right;
  }
}
</style>
