<template>
  <div class="our-case">
    <div class="container">
      <div class="choose-header">
        <b>OUR CASE</b>
        <span>STUDIES</span>
      </div>
      <P style="">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. At blanditiis
        alias illo adipisci maxime enim! Ipsa, reprehenderit, deleniti
        voluptates perferendis nesciunt vel ullam tempore explicabo blanditiis
        nam veniam possimus alias!Ipsa, reprehenderit, deleniti voluptates
        perferendis nesciunt vel ullam tempore explicabo blanditiis nam veniam
        possimus alias!
      </P>
      <div class="d-row" style="justify-content: center; padding-bottom: 100px">
        <div class="d-colAuto">ALL</div>
        <div class="d-colAuto">HOVER BUT</div>
        <div class="d-colAuto">AVTIVE BUT</div>
        <div class="d-colAuto">CATEGORY 3</div>
      </div>
      <div class="d-row">
        <div class="d-col3"></div>
        <div class="d-col3"></div>
        <div class="d-col3" style="background-color: #b6bfc4"></div>
        <div class="d-col3"></div>
        <div class="d-col3"></div>
        <div class="d-col3"></div>
        <div class="d-col3" style="background-color: #ced9de"></div>
        <div class="d-col3" style="background-color: #99a9b5"></div>
        <div class="d-col3"></div>
        <div class="d-col3" style="background-color: #99a9b5"></div>
        <div class="d-col3" style="background-color: #b6bfc4"></div>
        <div class="d-col3" style="background-color: #b6bfc4"></div>
      </div>
      <div
        class="d-flex"
        style="justify-content: space-between; padding: 100px 0"
      >
        <div class="double-br"></div>
        <button class="btn-work">MORE WORK</button>
        <div class="double-br"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.our-case {
  padding: 140px 0;
  .double-br {
    width: 40%;
    height: 4px;
    border-bottom: 1px solid #00bcd4;
    border-top: 1px solid #00bcd4;
    margin: 25px 0;
  }
  .btn-work {
    border-radius: 50px;
    font-size: 16px;
    padding: 17px 50px;
    border: 1px solid #00bcd4;
    color: #00bcd4;
    background-color: #fff;
  }
  .d-col3 {
    height: 300px;
    background-color: #dfe5e8;
  }
  p {
    color: #5f727f;
    text-align: center;
    font-size: 16px;
    padding: 80px 0;
  }
  .d-colAuto {
    padding: 5px 10px;
    background-color: #dfe5e8;
    margin-left: 15px;
    border-radius: 15px;
    color: #99a9b5;
  }
  .d-colAuto:hover {
    background-color: #99a9b5;
    color: #dfe5e8;
    cursor: pointer;
  }
}
</style>
