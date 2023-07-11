<script></script>
<template>
  <div class="header">
    <div class="header-area">
      <div class="header-box"></div>
      <div class="header-box2">
        <div class="header-box2-1"></div>
        <div class="header-box2-2"></div>
        <div class="header-box2-3"></div>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.header {
  width: 100%;
  height: 25%;
  // border: 3px solid black;
  display: flex;
  flex: content;
  align-items: center;
  justify-content: center;
  .header-area {
    width: 100%;
    display: flex;
    justify-content: space-between;
  }
  .header-box {
    width: 100px;
    height: 100px;
    background-image: url("https://i.pinimg.com/736x/a3/33/37/a333378371a3d75faf55f115617cb776.jpg");

    background-size: cover; /* 图片等比例缩放以填充容器 */
    background-position: center; /* 图片在容器中居中显示 */
    background-repeat: no-repeat; /* 防止图片重复显示 */
  }
  .header-box2 {
    padding-top: 25px;
    .header-box2-1,
    .header-box2-2,
    .header-box2-3 {
      width: 50px;
      height: 10px;
      background-color: black;
      border-radius: 10px;
      margin-bottom: 5px;
    }
    .header-box2-2 {
      background-color: black;
    }
    .header-box2-3 {
      background-color: black;
    }
  }
}
</style>
