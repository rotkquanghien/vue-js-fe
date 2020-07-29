<template>
  <div class="buy-it">
    <div class="container">
      <div class="d-row">
        <div class="d-col4 f-center">
          <span class="bold">THE</span>
          <img src="@/images/logo.png" alt="" />
          <span class="bold">GEM</span>
        </div>
        <div class="d-col4 d-center">
          <p class="font-mon" style="line-height: 28px">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos at
            officiis
          </p>
        </div>
        <div class="d-col4" style="padding: 20px">
          <button><b style="font-size: 19px">Great, I want to buy it now</b></button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.buy-it {
  .f-center {
    text-align: center;
  }
  .d-center {
    padding: 20px;
  }
  background-color: #ffcd46;
  padding: 70px 0;
  .bold {
    font-weight: 700;
    font-size: 63px;
    color: #3c3950;
  }

  button {
    width: 100%;
    color: #393d50;
    font-weight: 700;
    background-color: #ffcd46;
    border: 2px solid #393d50;
    padding: 15px 40px;
    border-radius: 30px;
  }
}
</style>
