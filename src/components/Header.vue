<template>
  <div class="header">
    <div class="header-top">
      <div class="container">
        <div class="d-row">
          <div class="sub-menu d-fixed">
            <i class="fa fa-bars" aria-hidden="true"></i>
            <ul id="sub">
              <li v-for="n in 7" :key="n">
                HOME
              </li>
            </ul>
          </div>
          <div class="d-col4 hidden" style="line-height: 50px">
            <span
              ><i
                class="fa fa-map-marker"
                aria-hidden="true"
                style="padding-right: 15px"
              ></i
              >&nbsp;&nbsp;<span
                style="font-family: 'Source Sans Pro', sans-serif;"
                >19th Ave New York, NY 95822, USA</span
              ></span
            >
            <span
              ><i
                class="fa fa-map-marker"
                aria-hidden="true"
                style="padding-left: 15px"
              ></i
              ><span style="font-family: 'Source Sans Pro', sans-serif;"
                >+1 916-85-2235</span
              ></span
            >
          </div>

          <div
            class="d-col4 hidden"
            style="line-height: 50px; text-align: center;"
          >
            <div class="icons">
              <i class="fa fa-facebook-official" aria-hidden="true"></i>
              <i class="fa fa-youtube-play" aria-hidden="true"></i>
              <i class="fa fa-google" aria-hidden="true"></i>
              <i class="fa fa-facebook-official" aria-hidden="true"></i>
              <i class="fa fa-youtube-play" aria-hidden="true"></i>
              <i class="fa fa-youtube-play" aria-hidden="true"></i>
              <i class="fa fa-google" aria-hidden="true"></i>
            </div>
          </div>
          <div class="d-col4" style="line-height: 50px;text-align: right">
            <span class="bread"><a>> Contact Us</a></span>
            <span class="bread"><a>> Sign In</a></span>
            <span class="bread"><a>> More Menu</a></span>
            <span class="bread"
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
                  <div class="d-colAuto menu-item">HOME</div>
                  <div class="d-colAuto menu-item">HOME</div>
                  <div class="d-colAuto menu-item">HOME</div>
                  <div class="d-colAuto menu-item">HOME</div>
                  <div class="d-colAuto menu-item">HOME</div>
                  <div class="d-colAuto menu-item">HOME</div>
                </div>
              </div>
              <div class="d-col3 hidden" style="padding: 15px">
                <i class="fa fa-flag cs-i" aria-hidden="true"></i>
                <i class="fa fa-search cs-i" aria-hidden="true"></i>
                <i class="fa fa-shopping-cart cs-i" aria-hidden="true"></i>
                <i class="fa fa-tag cs-i" aria-hidden="true">2</i>
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
            <span style="font-size: 27px; font-weight: 500">THE</span>
            <span style="font-size: 27px; font-weight: 700">GEM</span>
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
@media only screen and (max-width: 768px) {
  .sub-menu {
    display: block !important;
    position: absolute;
    z-index: 100;
  }
  .hidden {
    display: none;
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
  padding-left: 10px;
  font-family: "Source Sans Pro", sans-serif;
}
.icons .fa {
  padding-left: 10px;
}
.menu-item {
  font-weight: 700;
}
</style>
