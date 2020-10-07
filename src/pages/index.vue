<template>
  <div class="index-container">
    <div class="demo">123</div>
  </div>
</template>

<script>
export default {
  name: "index",
  data() {
    return {};
  },
};
</script>

<style lang="scss" scoped>
.index-container {
  position: relative;
  height: 100%;
  width: 100%;
  border: 55px solid gray;
  box-sizing: border-box;
  .demo {
    position: absolute;
    top: -50px;
    left: -50px;
  }
}
</style>