<script></script>
<template>
  <div class="home-area">
    <div class="text-area">
      <h1>title</h1>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Facere ab
        inventore, nulla alias tempore laborum rem ad at dolorum labore?
      </p>
    </div>
    <div class="img1"></div>
  </div>
</template>
<style lang="scss">
.home-area {
  // border: 3px solid red;
  width: 100%;
  display: flex;
  align-items: center;
  .text-area {
    padding-bottom: 48px;
    h1 {
      margin-left: 32px;
      margin-bottom: -20px;
      font-size: 64px;
    }
    p {
      font-size: 24px;
    }
  }
  .img1 {
    width: 50%;
    height: 300px;
    background-image: url(https://pboss.tw/wp-content/uploads/20210709223046_29.jpg);

    background-size: cover; /* 图片等比例缩放以填充容器 */
    background-position: center; /* 图片在容器中居中显示 */
    background-repeat: no-repeat; /* 防止图片重复显示 */
  }
}
</style>
