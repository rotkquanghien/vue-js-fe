<template>
  <div class="core">
    <div class="container" style="padding: 100px 0">
      <div class="choose-header" style="padding-bottom: 80px">
        <b style="color: white">CORE</b>
        <span style="color: white; font-family: 'Montserrat', sans-serif;"
          >COMPETENCE</span
        >
      </div>
      <p
        class="d-center"
        style="color: #fff; font-family: 'Source Sans Pro', sans-serif;"
      >
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae debitis
        nobis reprehenderit cupiditate ipsa voluptatibus, impedit optio possimus
        qui. Aperiam fugiat magnam qui illum saepe deleniti a consequuntur sit?
        Dolorem!nobis reprehenderit cupiditate ipsa voluptatibus, impedit optio
        possimus qui. Aperiam fugiat magnam qui illum saepe deleniti a
        consequuntur sit? Dolorem!
      </p>
    </div>
    <div class="evi">
      <div class="container iner">
        <div class="d-row">
          <div class="d-col6">
            <div class="evi-img d-center">
              <img src="@/images/bongden.png" alt="" />
            </div>
            <h2 class="d-center"><b>CONSULTING</b></h2>
            <p class="d-center">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit.
              Cupiditate eos omnis eius esse ipsa deserunt a porro, illum
              tempora consequuntur ullam perspiciatis temporibus facere, vero
              minus optio. Ad, quidem amet.
            </p>
            <div class="evi-btn d-center">
              <button>LEARN MORE</button>
            </div>
            <div class="d-line hidden">
              <div class="d-linee"></div>
            </div>
          </div>
          <div class="d-col6">
            <div class="evi-img d-center">
              <img src="@/images/HCN.png" alt="" style="height: 122px"/>
            </div>
            <h2 class="d-center"><b>PROGRAMING</b></h2>
            <p class="d-center">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit.
              Cupiditate eos omnis eius esse ipsa deserunt a porro, illum
              tempora consequuntur ullam perspiciatis temporibus facere, vero
              minus optio. Ad, quidem amet.
            </p>
            <div class="evi-btn d-center">
              <button>LEARN MORE</button>
            </div>
            <div class="d-line hidden">
              <div class="d-linee"></div>
            </div>
          </div>
        </div>
        <div class="d-row">
          <div class="d-col6">
            <div class="evi-img d-center">
              <img src="@/images/phone.png" alt="" />
            </div>
            <h2 class="d-center"><b>DEVELOPMENT</b></h2>
            <p class="d-center">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit.
              Cupiditate eos omnis eius esse ipsa deserunt a porro, illum
              tempora consequuntur ullam perspiciatis temporibus facere, vero
              minus optio. Ad, quidem amet.
            </p>
            <div class="evi-btn d-center">
              <button>LEARN MORE</button>
            </div>
          </div>
          <div class="d-col6">
            <div class="evi-img d-center">
              <img src="@/images/cups.png" alt="" />
            </div>
            <h2 class="d-center"><b>MAKETING</b></h2>
            <p class="d-center">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit.
              Cupiditate eos omnis eius esse ipsa deserunt a porro, illum
              tempora consequuntur ullam perspiciatis temporibus facere, vero
              minus optio. Ad, quidem amet.
            </p>
            <div class="evi-btn d-center">
              <button>LEARN MORE</button>
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
@media (max-width: 768px) {
  .d-col6:nth-child(1),.d-col6:nth-child(2) {
    border-radius: 0 !important;
  }
  .hidden{
    display: none;
  }
}
.core {
  .d-line {
    height: 1px;
    text-align: center;
    .d-linee {
      border-bottom: #5f727f 1px dashed;
      padding: 30px 0;
      width: 96%;
      margin: auto;
    }
  }
  .iner {
    background: linear-gradient(
      69deg,
      rgba(62, 165, 230, 1) 0%,
      rgba(62, 165, 230, 1) 13%,
      rgba(5, 209, 198, 1) 100%
    );
  }
  .evi {
    .d-row:nth-child(1) {
      .d-col6:nth-child(1) {
        border-radius: 0 50px 0 0;
      }
      .d-col6:nth-child(1)::before {
        content: "";
        display: block;
        position: absolute;
        height: 65%;
        border-left: #5f727f 1px dashed;
        width: 1px;
        right: 0;
      }

      .d-col6:nth-child(2) {
        border-radius: 50px 0px 0 0;
      }
    }
    .d-row:nth-child(2) {
      .d-col6:nth-child(1)::before {
        content: "";
        display: block;
        position: absolute;
        height: 60%;
        border-left: #5f727f 1px dashed;
        width: 1px;
        right: 0;
        top: 0;
      }
    }
    .evi-btn {
      padding-top: 60px;
      button {
        padding: 5px 20px;
        background-color: #393b51;
        border-radius: 15px;
        color: #00bcd4;
        border: solid 1px #00bcd4;
        font-size: 14px;
        font-family: "Montserrat", sans-serif;
        font-weight: 200;
      }
    }
    .evi-img {
      padding-bottom: 60px;
    }
    h2 {
      padding-bottom: 30px;
    }
    b {
      font-size: 28px;
      color: aliceblue;
    }
    p {
      font-size: 16px;
      color: #c9d8e3;
      font-weight: 100;
    }
    background-color: #393b51;
    .d-col6 {
      position: relative;
      padding: 120px 50px;
      background-color: #393b51;
    }
  }
  //   background: rgb(62, 165, 230);
  background: linear-gradient(
    69deg,
    rgba(62, 165, 230, 1) 0%,
    rgba(62, 165, 230, 1) 13%,
    rgba(5, 209, 198, 1) 100%
  );
}
</style>
