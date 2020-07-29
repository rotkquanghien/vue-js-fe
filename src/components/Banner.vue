<template>
  <div class="banner">
    <div class="arrow-left">
      <i class="fa fa-arrow-left" aria-hidden="true"></i>
    </div>
    <div class="container">
      <p class="wrap-text">
        <span class="the">THE</span>
        <span class="gem">GEM</span>
      </p>
      <p class="wrap-text">
        <span class="the">THE</span>
        <span class="gem">OPPORTUNITY.</span>
      </p>
      <p class="wrap-text" style=" font-weight: 200">
        <span style="font-size: 24px !important; text-transform: uppercase">Step Forward, Lead The Innovation</span>
      </p>
      <div class="wrap-text">
        <button class="btn-banner">
          <i class="fa fa-diamond" aria-hidden="true" style="font-size: 17px !important; padding-right: 10px"></i>
          <span class="font-mon" style="font-size: 19px">OUR SERVICES</span>
        </button>
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

<style>
.banner {
  background-color: #ebebeb;
  padding: 160px 0 80px 0;
  position: relative;
}
.the {
  font-size: 80px;
  font-weight: 200;
}
.gem {
  font-size: 80px;
  font-weight: 700;
}
.wrap-text {
  padding: 15px 0;
}
.btn-banner {
  padding: 10px 25px;
  background-color: #00bcd4;
  color: white;
  border: none;
  border-radius: 5px;
  font-weight: 700;
}
</style>
