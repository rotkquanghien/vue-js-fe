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
      <p class="wrap-text" style="font-size: 18px">
        <span>Step Forward, Lead The Innovation</span>
      </p>
      <div class="wrap-text">
        <button class="btn-banner">
          <i class="fa fa-diamond" aria-hidden="true"></i>
          OUR SERVICES
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
  padding: 100px 0 60px 0;
  position: relative;
}
.the {
  font-size: 40px;
  font-weight: 500;
}
.gem {
  font-size: 40px;
  font-weight: 700;
}
.wrap-text {
  padding: 15px 0;
}
.btn-banner {
  padding: 8px 10px;
  background-color: #00bcd4;
  color: white;
  border: none;
  border-radius: 5px;
  font-weight: 700;
}
</style>
