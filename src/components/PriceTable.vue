<template>
  <div class="price">
    <div class="container">
      <div class="choose-header">
        <b>PRICING</b>
        <span>TABLE</span>
      </div>
      <p class="d-center" style="padding: 80px 0">
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Cum accusamus
        nulla optio similique, numquam sint illum earum praesentium dolorum
        culpa laborum, provident quaerat saepe. Iure, quas. Neque explicabo
        maxime deserunt.nulla optio similique, numquam sint illum earum
        praesentium dolorum culpa laborum, provident quaerat saepe. Iure, quas.
        Neque explicabo maxime deserunt.
      </p>
      <div class="d-row">
        <div class="d-col3" v-for="data in ptData" :key="data">
          <h2 class="pt-header">
            {{ data.ptHeader }}
          </h2>
          <div class="pt-price" :class="data.ptColor">
            <h2 class="d-center">{{ data.ptPrice }}</h2>
            <p class="d-center">{{ data.ptTimes }}</p>
          </div>
          <p
            class="pt-content d-center"
            v-for="item in data.ptContent"
            :key="item"
          >
            {{ item }}
          </p>
          <div class="pt-btn d-center">
            <button class="d-center">
              <i class="fa fa-caret-right" aria-hidden="true"></i> <b>ORDER</b>
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      ptData: [
        {
          ptHeader: "BEGINNER",
          ptPrice: "$10",
          ptTimes: "Per Month",
          ptContent: [
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor "
          ],
          ptColor: "beginner"
        },
        {
          ptHeader: "ADVANCE",
          ptPrice: "$45",
          ptTimes: "Per Month",
          ptContent: [
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor "
          ],
          ptColor: "advance"
        },
        {
          ptHeader: "MASTER",
          ptPrice: "$249",
          ptTimes: "Per Month",
          ptContent: [
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor "
          ],
          ptColor: "master"
        },
        {
          ptHeader: "INSANE",
          ptPrice: "$1399",
          ptTimes: "Per Month",
          ptContent: [
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor ",
            "Lorem ipsum, dolor "
          ],
          ptColor: "insane"
        }
      ]
    };
  }
};
</script>

<style lang="scss">
.price {
  padding: 100px 0;
  .d-row {
    position: relative;
  }
  .d-col3 {
    border: solid 1px #dfe5e8;
  }
  .d-col3:hover {
    //   padding: 40px 0;
    transform: scaleY(1.05);
    .pt-header,
    .pt-btn,
    .pt-price,
    .pt-content {
      background-color: #fff;
    }
  }
  .beginner {
    background-color: #b0de79 !important;
  }
  .advance {
    background-color: #7ee0bf !important;
  }
  .master {
    background-color: #83bce9 !important;
  }
  .insane {
    background-color: #a289e8 !important;
  }
  .pt-btn {
    padding: 50px 0;
    background-color: #f0f3f2;
    button {
      padding: 10px 20px;
      background-color: #393d50;
      color: #ffffff;
      border-radius: 20px;
      border: none;
    }
    button:hover {
      background-color: #83bce9;
    }
  }
  .pt-header {
    padding: 40px 80px;
    background-color: #f0f3f2;
    text-align: center;
    font-size: 24px;
  }
  .pt-price {
    padding: 40px 60px;
    background-color: #b0de79;
    h2 {
      font-size: 65px;
      color: #ffffff;
      font-weight: 100;
    }
    p {
      font-size: 16px;
      color: #ffffff;
      font-weight: 100;
    }
  }
  .pt-content {
    padding: 25px 60px;
    background-color: #f0f3f2;
  }
  .pt-content:nth-child(-n + 7) {
    border-bottom: solid 1px #dfe5e8;
  }
  .pt-content:nth-child(n + 6) {
    color: #b0bdc5;
    text-decoration: line-through;
  }
  .pt-content:nth-child(1) {
    padding-top: 50px !important;
  }
}
</style>
