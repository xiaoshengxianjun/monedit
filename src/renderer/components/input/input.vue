<template>
  <div class="input-wrapper">
    <label>{{label}}：</label>
    <input type="text" :value="inputValue" placeholder="请输入内容">
  </div>
</template>
<script>
export default {
  data() {
    return {
      inputValue: this.value
    };
  },
  props: ["label", "value"],
  methods: {},
  mounted() {}
};
</script>

<style lang="scss" scoped>
.input-wrapper {
  overflow: hidden;
  line-height: 36px;
  margin: 10px 0px;
  label {
    float: left;
    margin-left: 20px;
  }
  input {
    width: 200px;
    height: 36px;
    float: left;
    padding: 0px 5px;
    border-radius: 8px;
    outline: none;
    border: 1px solid #ddd;
  }
}
</style>
