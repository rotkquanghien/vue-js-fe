<template>
  <footer>
    <div class="container">
      <div class="d-row">
        <div class="d-col3">
          <div class="ft-imgP">
            <img src="@/images/biglogo.png" alt="" />
          </div>
          <p class="non-pad">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Perferendis, nemo et? Deserunt natus ullam impedit vitae. Sequi
            magni, rerum iure quae repudiandae aperiam quia excepturi, quasi
            consequatur minus aliquid nobis?
          </p>
        </div>
        <div class="d-col3">
          <h2>
            USEFUL LINKS <i class="fa fa-caret-left red" aria-hidden="true"></i>
          </h2>
          <ul style="padding: 15px 0; line-height: 30px">
            <li v-for="n in 5" :key="n">
              <button class="dot"></button>
              <a href="">
                Lorem ipsum dolor sit amet.
              </a>
            </li>
          </ul>
        </div>
        <div class="d-col3">
          <h2>
            NETSLETTERS <i class="fa fa-caret-left red" aria-hidden="true"></i>
          </h2>
          <p style="padding: 15px 0 36px 0;">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Numquam
            optio ipsam fuga quasi doloremque dignissimos illum voluptates quis
          </p>
          <div class="input-email">
            <input type="text" placeholder="Your email address" />
            <div class="icon">
              <i class="fa fa-chevron-right" aria-hidden="true"></i>
            </div>
          </div>
          <p>
            <span style="color: #00bcd4">*</span
            ><span
              style="color: #4a4b5b; font-size: 12px; font-family: 'Source Sans Pro', sans-serif;"
              >Personal information will be encrypted</span
            >
          </p>
        </div>
        <div class="d-col3">
          <h2>
            RECENT POSTS <i class="fa fa-caret-left red" aria-hidden="true"></i>
          </h2>
          <div class="wrap-post">
            <div class="post" style=" border-bottom: solid 1px #394050">
              <div class="d-row">
                <div class="d-col3 ">
                  <div class="igm"></div>
                </div>
                <div class="d-col9">
                  <p class="non-pad ver-pad">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  </p>
                  <div
                    class="d-row h15" 
                    style="justify-content: space-between; padding-top:10px"
                  >
                    <div class="d-colAuto">
                      <span style="color: #00bcd4">2017 Dec 15</span>
                    </div>
                    <div class="d-colAuto">
                      <i
                        class="fa fa-comments"
                        aria-hidden="true"
                        style="color: #ccd4da"
                        ><span style="color: #ccd4da" class="h15">14</span></i
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="post">
              <div class="d-row">
                <div class="d-col3 ">
                  <div class="igm"></div>
                </div>
                <div class="d-col9">
                  <p class="non-pad ver-pad">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  </p>
                  <div
                    class="d-row h15 "
                    style="justify-content: space-between; padding-top:10px"
                  >
                    <div class="d-colAuto">
                      <span style="color: #00bcd4">2017 Dec 15</span>
                    </div>
                    <div class="d-colAuto">
                      <i
                        class="fa fa-comments"
                        aria-hidden="true"
                        style="color: #ccd4da"
                        ><span style="color: #ccd4da" class="h15">12</span></i
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="foot" style="background-color: #181828; padding: 50px 0">
      <div class="container">
        <div class="d-row">
          <div class="d-col3 col-md">
            <span>© Copyright 2015 </span>
            <span style="color: #00bcd4">CodexThemes</span>
          </div>
          <div class="d-col6 col-md" style="padding: 0 30px">
            <div class="d-row ">
              <div
                class="d-col3 font-mon"
                style="border-right: solid 1px #394050; color: #77828f"
              >
                Support
              </div>
              <div
                class="d-col3 font-mon"
                style="border-right: solid 1px #394050; color: #77828f"
              >
                Contact Us
              </div>
              <div
                class="d-col3 font-mon"
                style="border-right: solid 1px #394050; color: #77828f"
              >
                Disclaim
              </div>
              <div class="d-col3" style="color: #77828f">Privacy Policy</div>
            </div>
          </div>
          <div class="d-col3 col-md">
            <div class="icons">
              <i
                class="fa fa-twitter"
                aria-hidden="true"
                style="color: #16a7b9"
              ></i>
              <i
                class="fa fa-facebook"
                aria-hidden="true"
                style="color: #315bd6"
              ></i>
              <i
                class="fa fa-instagram"
                aria-hidden="true"
                style="color: #0288d1"
              ></i>
              <i
                class="fa fa-facebook-official"
                aria-hidden="true"
                style="color: #786f4c"
              ></i>
              <i
                class="fa fa-youtube-play"
                aria-hidden="true"
                style="color: red"
              ></i>
              <i class="fa fa-youtube-play" aria-hidden="true"></i>
              <i
                class="fa fa-pinterest-p"
                aria-hidden="true"
                style="color: #ff5757"
              ></i>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss">
@media (max-width: 868px){
  .font-mon{
    border: none !important;
  }
  .col-lg{
    flex: 0 0 100% !important;
    max-width: 100% !important;
  }
  .h15{
    padding: 0 !important;
  }
}
footer {
  .h15{
    padding: 0 10px;
  }
  .post {
    i:hover {
      color: #00bcd4 !important;
      span {
        color: #00bcd4 !important;
      }
    }
  }
  .foot {
    .d-col3 {
      color: #fff;
      text-align: center;
    }
  }
  padding-top: 100px;

  .d-col3 {
    padding: 0 10px;
  }
  .ft-imgP {
    padding: 25px 0;
  }
  p,
  span,
  li,
  a {
    color: #99a9b5;
  }
  .post {
    padding: 15px 0;
  }
  .d-col9 {
    padding: 0 15px;
  }
  .igm {
    width: 70px;
    height: 70px;
    border-radius: 50%;
    background-color: #99a9b5;
  }
  input {
    padding: 8px 10px;
    background-color: #181828;
    color: #ccd4da;
    border: 1px solid #394050;
    font-size: 14px;
  }
  .icon {
    display: inline-block;
    background-color: #394050;
    padding: 10px 10px;
    color: #ccd4da;
    border-radius: 0 3px 3px 0;

    position: relative;
    top: -1px;
    left: -3px;
  }
  .dot {
    width: 4px;
    height: 4px;
    border: none;
    background-color: #00bcd4;
    border-radius: 50%;
  }
  li {
    padding: 5px 0;
  }
  li:hover {
    a {
      color: #00bcd4;
    }
    .dot {
      background-color: #fff;
    }
  }
  p{
    padding: 0 10px;
  }
  h2 {
    color: #ffffff;
    font-size: 19px;
    padding: 40px 0;
  }
  p,
  a {
    font-size: 16px;
    line-height: 25px;
  }
  a {
    text-decoration: none;
  }
  ul {
    list-style-type: none;
  }
  .red {
    color: red;
    transform: rotate(-46deg);
    position: relative;
    bottom: -6px;
  }
  background-color: #212331;
}
</style>
