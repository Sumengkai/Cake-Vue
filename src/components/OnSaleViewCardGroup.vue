<script>
export default {
  props: ["imgBcg", "buttonValue", "btnColor"],
};
</script>
<template>
  <div class="box1 box">
    <div class="box-img" :style="imgBcg"></div>
    <div class="btn-group">
      <button class="btn" style="background-color: {{ btnColor }}">
        {{ buttonValue }}
      </button>
    </div>
  </div>
</template>
<style lang="scss">
.box {
  width: 30%;
  height: 400px;
  background-color: pink;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  .box-img {
    width: 100%;
    height: 70%;
    background-size: cover; /* 图片等比例缩放以填充容器 */
    background-position: center; /* 图片在容器中居中显示 */
    background-repeat: no-repeat; /* 防止图片重复显示 */
  }
  .btn-group {
    width: 50%;
    .btn {
      background-color: navajowhite;
      margin-bottom: 10px;
    }
  }
}
</style>
