<template>
  <div class="case">
    <div class="d-row">
      <div
        class="d-col4"
        style="background-color: #00bcd4; padding: 0 40px 30px 30px;"
      >
        <div class="case-num">01 .</div>
        <div class="case-name">
          LOREM <b>IPSUM</b>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus,
            ullam nesciunt.
          </p>
        </div>
      </div>
      <div
        class="d-col4"
        style="background-color: #37394c; padding: 0 40px 30px 30px;"
      >
        <div class="case-num">02 .</div>
        <div class="case-name">
          LOREM <b>IPSUM</b>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus,
            ullam nesciunt.
          </p>
        </div>
      </div>
      <div
        class="d-col4"
        style="background-color: #aed581; padding: 0 40px 30px 30px;"
      >
        <div class="case-num">03 .</div>
        <div class="case-name">
          LOREM <b>IPSUM</b>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus,
            ullam nesciunt.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.case {
  .case-num {
    color: aliceblue;
    padding: 70px 0;
    font-size: 70px;
    font-weight: 700;
  }
  .case-name {
    color: aliceblue;
    font-size: 36px;
    b {
      font-size: 36px;
      color: #e7ff89;
    }
  }
  p {
    padding-top: 30px;
    width: 70%;
    color: black;
  }
}
</style>
