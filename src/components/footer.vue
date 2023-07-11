<script></script>
<template>
  <div class="footer-area">
    <div class="bg">
      <div class="bg-img"></div>
    </div>
    <div class="bg-p-box">
      <div class="bg-p">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem quis
          laborum ut labore, vel quas blanditiis facilis est adipisci magnam
          praesentium debitis eligendi dolore esse iste quod pariatur id sunt!
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem quis
          laborum ut labore, vel quas blanditiis facilis est adipisci magnam
          praesentium debitis eligendi dolore esse iste quod pariatur id sunt!
        </p>
      </div>
    </div>
  </div>
</template>
<style lang="scss">
.footer-area {
  width: 100%;
  height: 600px;

  // border: 3px solid red;
  display: flex;
  align-items: center;
  justify-content: space-between;
  .bg {
    width: 50%;
    height: 500px;
    background-color: pink;
    .bg-img {
      width: 100%;
      height: 70%;
      background-image: url(https://watermark.lovepik.com/photo/40010/7045.jpg_wh1200.jpg);
      background-size: cover; /* 图片等比例缩放以填充容器 */
      background-position: center; /* 图片在容器中居中显示 */
      background-repeat: no-repeat; /* 防止图片重复显示 */
      position: relative;
      left: 25%;
      top: 15%;
    }
  }
  .bg-p-box {
    width: 30%;
    height: 500px;
    background-color: pink;
    display: flex;
    justify-content: center;
    align-items: center;
    .bg-p {
      width: 80%;
      p {
        text-align: center;
      }
    }
  }
}
</style>
