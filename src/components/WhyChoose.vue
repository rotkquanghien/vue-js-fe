<template>
  <div class="choose">
    <div class="container">
      <div class="choose-header">
        <b>WHY</b>
        <span>CHOOSING US</span>
      </div>
      <div class="d-row">
        <div class="d-col4">
          <div class="d-row">
            <div class="cirr"></div>
            <div style="width: 75%; padding: 0 20px">
              <p class="choose-tittle">LOREM IPSUM</p>
              <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Similique dolorem quae officiis quisquam est ut
              </p>
            </div>
          </div>
        </div>
        <div class="d-col4">
          <div class="d-row">
            <div class="cirr"></div>
            <div style="width: 75%; padding: 0 20px">
              <p class="choose-tittle">LOREM IPSUM</p>
              <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Similique dolorem quae officiis quisquam est ut
              </p>
            </div>
          </div>
        </div>
        <div class="d-col4">
          <div class="d-row">
            <div class="cirr"></div>
            <div style="width: 75%; padding: 0 20px">
              <p class="choose-tittle">LOREM IPSUM</p>
              <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Similique dolorem quae officiis quisquam est ut
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="d-row">
        <div class="d-col4">
          <div class="cs-br"></div>
          <div class="d-row">
            <div class="cirr"></div>
            <div style="width: 75%; padding: 0 20px">
              <p class="choose-tittle">LOREM IPSUM</p>
              <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Similique dolorem quae officiis quisquam est ut
              </p>
            </div>
          </div>
        </div>
        <div class="d-col4">
          <div class="cs-br"></div>
          <div class="d-row">
            <div class="cirr"></div>
            <div style="width: 75%; padding: 0 20px">
              <p class="choose-tittle">LOREM IPSUM</p>
              <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Similique dolorem quae officiis quisquam est ut
              </p>
            </div>
          </div>
        </div>
        <div class="d-col4">
          <div class="cs-br"></div>
          <div class="d-row">
            <div class="cirr"></div>
            <div style="width: 75%; padding: 0 20px">
              <p class="choose-tittle">LOREM IPSUM</p>
              <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Similique dolorem quae officiis quisquam est ut
              </p>
            </div>
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
.choose {
  background-color: #f0f3f2;
  padding: 100px 0;
  .cs-br {
    height: 2px;
    background-color: #d6dde0;
    width: 90%;
  }
  .d-row:nth-child(1) .d-col4 {
    border-top: solid 2px #46485c;
  }
  .d-col4 {
    padding: 20px 0;
  }
  .cirr {
    position: relative;
    transform: translateY(79%);
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: #46485c;
  }

  .choose-tittle {
    font-size: 19px;
    font-weight: 500;
    color: #8f9da5;
    padding: 40px 0;
  }
  p {
    font-size: 16px;
    color: #8f9da5;
  }
}
</style>
