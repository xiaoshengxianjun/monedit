<template>
  <div class="landing-page">
    <div class="login-wrapper">
      <div class="logo-box">
        <img src="../assets/logo.jpg" alt>
      </div>
      <input-component label="邮箱"></input-component>
      <input-component label="密码"></input-component>
    </div>
    <div class="news-wrapper">新闻信息页</div>
  </div>
</template>
<script>
import InputComponent from "@/components/input/input";

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
    min-width: 300px;
    height: 100%;
    background: red;
    float: left;
    text-align: center;
    .logo-box {
      width: 100%;
      img{
        width: 100px;
        height: 100px;
        margin-top: 20px;
      }
    }
  }
  .news-wrapper {
    width: 70%;
    height: 100%;
    // background: blue;
    float: right;
  }
}
</style>
