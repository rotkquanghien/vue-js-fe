<template>
  <div class="banner2">
    <div class="arrow-left">
      <i class="fa fa-arrow-left" aria-hidden="true"></i>
    </div>
    <div class="container">
      <div class="tron"></div>
      <div class="banner2-wrap">
        <h2>JENIFER BURNS</h2>
        <P>Creative Heads Inc.</P>
      </div>
      <p style="width: 70%; margin: auto">
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Magnam culpa
        alias sit! Quasi, sint facere. Laborum asperiores natus sit hic
        corrupti. Vel dicta inventore harum in porro architecto fuga iure.
      </p>
      <div class="banner-img">
        <img src="@/images/nhay.png" alt="" />
      </div>
    </div>
    <div class="arrow-right">
      <i class="fa fa-arrow-right" aria-hidden="true"></i>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.banner2 {
  position: relative;
  padding: 100px 0;
  background-color: #f1f1f2;
  .banner2-wrap {
    padding: 20px 0;
  }
  h2 {
    color: #20c3d8;
    font-size: 16px;
  }
  p {
    padding-bottom: 40px;
  }
  padding: 100px 0;
  h2,
  p,
  .banner-img {
    text-align: center;
  }
  .tron {
    margin: auto;
    width: 80px;
    height: 80px;
    border-radius: 50%;
    background-color: #b6c6c9;
  }
}
</style>
