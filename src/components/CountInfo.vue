<template>
  <div class="count-info">
    <div class="container">
      <div class="d-row">
        <div class="d-col3">
          <div class="cir">
            <div class="cle">
              <div>
                <img src="@/images/compa.png" alt="" />
              </div>
            </div>
          </div>
          <h2>2189</h2>
          <p>SUPPORT POSTS</p>
        </div>
        <div class="d-col3">
          <div class="cir" style="border: solid 4px #7ee0bf;">
            <div class="cle" style="border: solid 2px #7ee0bf; color: #7ee0bf">
              <div>
                <img src="@/images/compa.png" alt="" />
              </div>
            </div>
          </div>
          <h2 style="color: #7ee0bf">2189</h2>
          <p>SUPPORT POSTS</p>
        </div>
        <div class="d-col3">
          <div class="cir" style="border: solid 4px #83bce9;">
            <div class="cle" style="border: solid 2px #83bce9; color: #83bce9">
              <div>
                <img src="@/images/compa.png" alt="" />
              </div>
            </div>
          </div>
          <h2 style="color: #83bce9">2189</h2>
          <p>SUPPORT POSTS</p>
        </div>
        <div class="d-col3">
          <div class="cir" style="border: solid 4px #947fd3;">
            <div class="cle" style="border: solid 2px #947fd3; color: #947fd3">
              <div>
                <img src="@/images/compa.png" alt="" />
              </div>
            </div>
          </div>
          <h2 style="color: #947fd3">2189</h2>
          <p>SUPPORT POSTS</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.count-info {
  .d-col3 {
    .cir,
    h2,
    p {
      margin: auto !important;
    }
  }
}
@media only screen and (max-width: 576px) {
  .count-info {
    .d-col3 {
      .cir,
      h2,
      p {
        margin: auto !important;
      }
    }
  }
}
.count-info {
  background-color: #3a3c4b;
  padding: 130px 0;
  h2 {
    text-align: center;
    padding: 20px 0;
    width: 62%;
    font-size: 50px;
    font-weight: 100;
    color: #b0de79;
  }
  p {
    font-size: 24px;
    text-align: center;
    width: 70%;
    color: #cccccc;
  }
  .cir {
    width: 175px;
    height: 175px;
    border-radius: 50%;
    border: solid 4px #b0de79;
    padding: 6px 6px 6px 6px;
  }
  .cle {
    div {
      padding: 18%;
    }
    width: 100%;
    height: 100%;
    border-radius: 50%;
    border: solid 2px #b0de79;
    position: relative;
    margin: 0px 0px 0px 0;
  }
}
</style>
