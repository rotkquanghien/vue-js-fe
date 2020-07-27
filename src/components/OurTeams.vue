<template>
  <div class="our-team">
    <div class="container">
      <div class="d-row">
        <div class="d-col4">
          <h2>OUR TEAMS</h2>
          <div class="person" v-for="person in people" :key="person">
            <div
              class="d-row"
              style="padding: 40px 20px; background-color: #f0f3f2; margin-bottom: 22px"
            >
              <div class="d-col3" style="padding: 15px 0">
                <div class="or-cl3"></div>
              </div>
              <div class="d-col9">
                <p class="or-name">{{ person.name }}</p>
                <p class="or-pos">{{ person.position }}</p>
                <h4>{{ person.phone }}</h4>
              </div>
            </div>
          </div>
        </div>
        <div class="d-col8">
          <h2>OPEN VACANCIES</h2>
          <div class="or-group-button">
            <button class="or-btn" v-for="n in buttonNames" :key="n">
              {{ n }}
            </button>
          </div>
          <div class="detail-jobs">
            <div class="d-row">
              <div class="d-col6">
                <div class="dt-wrap">
                  <img src="@/images/logo.png" alt="" />
                </div>
              </div>
              <div class="d-col6">
                <h2>WEB DESIGNER</h2>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Doloribus deleniti possimus at praesentium consectetur aperiam
                  molestiae non iusto nihil quaerat quasi, sint quos rerum
                  dolorum in? Optio odio facilis molestias!Lorem ipsum dolor sit
                  amet consectetur adipisicing elit. Doloribus deleniti possimus
                  at praesentium consectetur aperiam molestiae non iusto nihil
                  quaerat quasi, sint quos rerum dolorum in? Optio odio facilis
                  molestias!
                </p>
              </div>
            </div>
            <div class="d-row">
              <div class="d-col6">
                <ul>
                  <li v-for="cont in jobContent" :key="cont">
                    <button class="square"></button>{{ cont }}
                  </li>
                </ul>
              </div>
              <div class="d-col6">
                <ul>
                  <li v-for="cont in jobContent" :key="cont">
                    <button class="square"></button>{{ cont }}
                  </li>
                </ul>
              </div>
            </div>
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
      people: [
        {
          name: "Emerson Anderson",
          position: "Senior Sale Manager",
          phone: "123456789"
        },
        {
          name: "Emerson Anderson",
          position: "Senior Sale Manager",
          phone: "123456789"
        },
        {
          name: "Emerson Anderson",
          position: "Senior Sale Manager",
          phone: "123456789"
        }
      ],
      buttonNames: ["WebDesigner", "WebDesigner", "WebDesigner", "WebDesigner"],
      jobContent: [
        "Lorem ipsum dolor sit amet",
        "Lorem ipsum dolor sit amet",
        "Lorem ipsum dolor sit amet",
        "Lorem ipsum dolor sit amet"
      ]
    };
  }
};
</script>

<style lang="scss">
.our-team {
  padding: 100px 0;
  .or-group-button {
    margin-left: 20px;
  }
  .detail-jobs {
    border: 1px solid #a5b3bd;
    padding: 50px;
    margin-left: 40px;
    margin-top: 20px;
    .square {
      width: 5px;
      height: 5px;
      background-color: #00bcd4;
      border: none;
      position: relative;
      top: -2px;
      margin-right: 10px;
    }
    ul {
      list-style: none;
      li {
        padding: 5px 0;
        color: #a5b3bd;
        font-size: 16px;
        font-weight: 500;
      }
    }
    p {
      color: #7f8e99;
      font-size: 16px;
      font-weight: 500;
      line-height: 23px;
    }
    h2 {
      padding-bottom: 30px;
    }
    .dt-wrap {
      padding: 30px;
      img {
        width: 100%;
      }
    }
  }
  .or-btn {
    background-color: #f4f6f7;
    min-width: 20%;
    color: #7f8e99;
    font-weight: 100;
    border: 1px solid #f4f6f7;
    margin-left: 20px;
    height: 50px;
    line-height: 50px;
  }
  .or-btn:hover {
    background-color: #fff;
    font-weight: 700;
    border: 1px solid #7f8e99;
  }
  .or-cl3 {
    width: 75px;
    height: 75px;
    background-color: #a5b3bd;
    border-radius: 50%;
  }
  h4 {
    color: #00bcd4;
    font-weight: 700;
  }
  .or-pos {
    font-size: 14px;
    color: #a5b3bd;
    font-weight: 100;
    padding-bottom: 15px;
  }
  .or-name {
    font-size: 24px;
    font-weight: 200;
    padding: 10px 0;
  }
  h2 {
    font-size: 24px;
    padding-bottom: 50px;
  }
}
</style>
