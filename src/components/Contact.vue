<template>
  <div class="contact">
    <div class="container">
      <div class="d-row">
        <div class="d-col3 p15 pd-60" v-for="(info, index) in dataInfo" :key="index">
          <div class="contact-img d-center">
            <img :src="require(`@/images/${info.img}.png`)" alt="" />
          </div>
          <div class="contact-name ">
            <h2 class="d-center">{{ info.name }}</h2>
          </div>
          <div class="contact-content">
            <p v-for="ct in info.content" :key="ct" class="d-center">
              {{ ct }}
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="d-row" style="padding-top: 60px">
      <div class="col6"></div>
      <div class="col6"></div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      dataInfo: [
        {
          img: "address",
          name: "ADDRESS",
          content: [
            "908 New Hampshire Avenue ",
            "Northwest #100, Washington, DC20037,",
            " United States"
          ]
        },
        {
          img: "iphones",
          name: "PHONE",
          content: [
            "Phone: 123456789 ",
            "Mobile: 1234567890",
            "Fax: 1234567890"
          ]
        },
        {
          img: "contact",
          name: "CONTACT",
          content: [
            "abc@gmail.com",
            " abceee@gmail.com",
            " abceeeeeeeeeeee@gmail.com"
          ]
        },
        {
          img: "clocks",
          name: "WORKING HOURS",
          content: [
            "Mon - Fri: 8am - 6pm ",
            "Sat: 8am - 12am",
            "Sun: Closed"
          ]
        }
      ]
    };
  }
};
</script>

<style lang="scss">
.contact {
  .col6 {
    width: 50%;
    height: 450px;
    background-color: #ccd4da;
  }
  .d-row {
    .col6:nth-child(1) {
      border-radius: 0 50px 0 0;
    }
    .col6:nth-child(2) {
      border-radius: 50px 0 0 0;
    }
  }
  padding-top: 100px;
  background-color: #414352;
  h2 {
    color: #ffffff;
    font-weight: 200;
    font-size: 24px;
    padding: 25px 0;
  }
  .contact-content {
    line-height: 25px;
    .d-center {
      color: #99a9b5;
    }
  }
}
</style>
