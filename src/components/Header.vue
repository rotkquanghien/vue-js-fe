<template>
  <div class="header">
    <div class="header-top">
      <div class="container">
        <div class="d-row" style="padding: 10px 0">
          <div class="sub-menu d-fixed">
            <i class="fa fa-bars" aria-hidden="true"></i>
            <ul id="sub">
              <li v-for="n in 7" :key="n">
                HOME
              </li>
            </ul>
          </div>
          <div class="d-col4 hidden" style="padding: 5px 0">
            <span
              ><i
                class="fa fa-map-marker"
                aria-hidden="true"
                style="padding-right: 5px"
              ></i
              >&nbsp;<span
                style="font-family: 'Source Sans Pro', sans-serif; color: #5f727f "
                >19th Ave New York, NY 95822, USA</span
              ></span
            >
            &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <span
              ><i
                class="fa fa-map-marker"
                aria-hidden="true"
                style="padding-right: 5px"
              ></i
              ><span
                style="font-family: 'Source Sans Pro', sans-serif; color: #5f727f "
                >+1 916-85-2235</span
              ></span
            >
          </div>

          <div class="d-col4 hidden col-mid" style="flex: 0 0 28%; padding: 5px 0">
            <div class="icons">
              <i class="fa fa-twitter" aria-hidden="true"></i>
              <i class="fa fa-facebook" aria-hidden="true"></i>
              <i class="fa fa-instagram" aria-hidden="true"></i>
              <i class="fa fa-facebook-official" aria-hidden="true"></i>
              <i
                class="fa fa-youtube-play"
                aria-hidden="true"
                style="color: red"
              ></i>
              <i class="fa fa-youtube-play" aria-hidden="true"></i>
              <i class="fa fa-pinterest-p" aria-hidden="true"></i>
            </div>
          </div>
          <div
            class="d-col4 col-lg"
            style="
                  text-align: right;
                  flex: 0 0 38.6%;
                  max-width: 38%;
                 "
          >
            <span class="bread"
              ><a
                ><i class="fa fa-chevron-right" aria-hidden="true"></i> Contact
                Us</a
              ></span
            >
            <span class="bread"
              ><a
                ><i class="fa fa-chevron-right" aria-hidden="true"></i> Sign
                In</a
              ></span
            >
            <span class="bread"
              ><a
                ><i class="fa fa-chevron-right" aria-hidden="true"></i> More
                Menu</a
              ></span
            >
            <span class="bread" style="padding-left: 30px;"
              ><button class="btn-join">Join Now</button></span
            >
          </div>
        </div>
      </div>
    </div>
    <div
      class="header-menu"
      style="box-shadow: 0px 1px 1px #888, 0px -1px 1px #888;"
    >
      <div class="container">
        <div class="d-row">
          <div class="d-col9 hidden" style="padding: 20px 0">
            <div class="d-row">
              <div class="d-col9 hidden">
                <div
                  class="d-row"
                  style="justify-content: space-between; line-height: 50px;"
                >
                  <div
                    class="d-colAuto menu-item"
                    v-for="menu in menu"
                    :key="menu"
                  >
                    {{ menu }}
                  </div>
                </div>
              </div>
              <div
                class="d-col3 hidden"
                style="padding: 15px; text-align: right"
              >
                <img src="@/images/coanh.png" alt="" style="padding: 0 15px" />
                <i class="fa fa-search cs-i" aria-hidden="true"></i>
                <i
                  class="fa fa-shopping-basket"
                  aria-hidden="true"
                  style="padding-right: 10px"
                ></i>
                <span class="rectangle d-center">2</span>
              </div>
            </div>
          </div>
          <div
            class="d-col3 f-center"
            style="line-height: 50px; text-align: right; padding: 18px 0"
          >
            <img
              src="@/images/logo.png"
              alt=""
              style="position: relative; top: 7px; width: 12%"
            />
            <span style="font-size: 27px; font-weight: 200">THE</span>
            <span style="font-size: 27px; font-weight: 700">GEM</span>
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
      menu: [
        "HOME",
        "PAGES",
        "BLOG",
        "PORTFOLIOS",
        "SHOP",
        "FEATURE",
        "ELEMENT"
      ]
    };
  }
};
</script>

<style lang="scss">
.col-mid {
  text-align: center;
  border-left: 1px solid #dfe5e8;
  border-right: 1px solid #dfe5e8;
}
.rectangle {
  display: inline-block;
  width: 20px;
  height: 16px;
  background: #00bcd4;
  color: #f4f6f7;
  position: relative;
}
.rectangle::before {
  content: "";
  width: 0;
  height: 0;
  border-top: 8px solid transparent;
  border-right: 12px solid #00bcd4;
  border-bottom: 8px solid transparent;
  position: absolute;
  left: -11px;
}
.fa-chevron-right {
  font-size: 11px !important;
}
.sub-menu:hover #sub {
  display: block !important;
}
.d-fixed {
  position: fixed !important;
}
.sub-menu {
  display: none;
  top: 10px;
  li {
    padding: 10px 25px;
    background-color: #494c64;
    color: #f4f6f7;
    font-weight: 500;
    font-family: "Montserrat", sans-serif;
    cursor: pointer;
  }
  li:hover {
    background-color: #f4f6f7;
    color: #494c64;
  }
  i {
    font-size: 35px !important;
    position: fixed;
    z-index: 15;
  }
  i:hover #sub {
    display: block !important;
  }
  position: relative;
  #sub {
    top: 30px;
    position: absolute;
    z-index: 50;
    display: none;
  }
}
.hidden {
  display: block;
}
@media (max-width: 1080px) {
  .col-lg {
    flex: 0 0 100% !important;
    max-width: 100% !important;
  }
  .sub-menu {
    display: block !important;
    position: absolute;
    z-index: 100;
  }
  .hidden {
    display: none !important;
  }
  .f-center {
    text-align: center !important;
    flex: 0 0 100% !important;
    max-width: 100% !important;
  }
}
.cs-i {
  padding-right: 15px;
}
i {
  font-size: 20px !important;
}
.btn-join {
  background-color: #494c64;
  font-weight: 500;
  border: none;
  padding: 8px 13px;
  color: #f4f6f7;
  border-radius: 3px;
}
.header {
  border-top: solid 4px #00bcd4;
  min-height: 50px;
}
.header-top {
  background-color: #f4f6f7;
}
.bread {
  padding: 0 10px;
  font-family: "Source Sans Pro", sans-serif;
  color: #5f727f;
}
.icons .fa {
  padding: 0 9px;
}
.menu-item {
  font-size: 14px;
  font-weight: 800;
  font-family: "Montserrat", sans-serif;
}
</style>
