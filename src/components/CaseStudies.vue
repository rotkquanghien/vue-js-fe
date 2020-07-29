<template>
  <div class="case">
    <div class="d-row">
      <div
        class="d-col4"
        style="background-color: #00bcd4; padding: 0px 40px 55px 30px;"
      >
        <div class="case-num font-mon">01 .</div>
        <div class="case-name">
          <span class="font-mon">LOREM</span> <b>IPSUM</b>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit
          </p>
        </div>
      </div>
      <div
        class="d-col4"
        style="background-color: #37394c; padding: 0px 40px 55px 30px;"
      >
        <div class="case-num font-mon">02 .</div>
        <div class="case-name">
          <span class="font-mon">LEFT SIDE</span> <b>ALIGNING</b>
          <p style="color: aliceblue">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
          </p>
        </div>
      </div>
      <div
        class="d-col4"
        style="background-color: #aed581; padding: 0px 40px 55px 30px;"
      >
        <div class="case-num font-mon">03 .</div>
        <div class="case-name">
          <span class="font-mon">CURUS</span> <b>MAURIS</b>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
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
    font-family: 'Montserrat', sans-serif !important;
  }
  .case-name {
    color: aliceblue;
    font-size: 36px;
    b {
      font-size: 36px;
      color: #e7ff89;
    }
    span{
      font-size: 36px;
      font-weight: 200;
    }
    p {
      font-family: 'Source Sans Pro', sans-serif;;
      font-size: 24px;
      font-weight: 200;
    }
  }
  p {
    padding-top: 30px;
    width: 80%;
    color: black;
  }
}
</style>
