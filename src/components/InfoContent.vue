<template>
  <div class="info">
    <div class="container">
      <div class="d-row">
        <div class="d-col4">
          <div class="info-content">
            <div><img src="@/images/icons.png" alt="" /></div>
            <h2 class="">Lorem ipsum dolor sit</h2>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Blanditiis atque deserunt aperiam iste ratione cumque velit
              veritatis delectus?
            </p>
            <button class="btn-info"></button>
          </div>
        </div>
        <div class="d-col4">
          <div class="info-content">
            <div><img src="@/images/bags.png" alt="" /></div>
            <h2 class="">Lorem ipsum dolor sit</h2>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Blanditiis atque deserunt aperiam iste ratione cumque velit
              veritatis delectus?
            </p>
            <button class="btn-info"></button>
          </div>
        </div>
        <div class="d-col4">
          <div class="info-content">
            <div><img src="@/images/tivi.png" alt="" /></div>
            <h2 class="">Lorem ipsum dolor sit</h2>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Blanditiis atque deserunt aperiam iste ratione cumque velit
              veritatis delectus?
            </p>
            <button class="btn-info"></button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.info {
  padding: 100px 0;
}
.info-content {
  position: relative;
  h2 {
    font-size: 30px;
    width: 60%;
    padding: 30px 0;
    text-transform: uppercase;
    color: #3c3950;
    line-height: 40px;
  }
  p {
    width: 70%;
    padding-bottom: 50px;
    color: #b4bdc3;
    line-height: 26px;
  }
  .btn-info {
    width: 150px;
    height: 30px;
    background-color: #00bcd4;
    border-radius: 5px;
    border: none;
  }
  img {
    position: absolute;
    right: 10%;
    top: 12%;
  }
}
</style>
