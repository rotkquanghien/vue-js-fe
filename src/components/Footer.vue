<template>
  <footer>
    <div class="container">
      <div class="d-row">
        <div class="d-col3">
          <div class="ft-imgP">
            <img src="@/images/biglogo.png" alt="" />
          </div>
          <p>
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
          <ul>
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
          <p style="padding-bottom: 25px">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Numquam
            optio ipsam fuga quasi doloremque dignissimos illum voluptates quis
          </p>
          <div class="input-email">
            <input type="text" placeholder="Your email address" />
            <div class="icon"><b>></b></div>
          </div>
          <p>
            <span style="color: #00bcd4">*</span
            ><span
              style="color: #4a4b5b; font-size: 14px; font-family: 'Source Sans Pro', sans-serif;"
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
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  </p>
                  <div
                    class="d-row"
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
                      ></i
                      ><span style="color: #ccd4da">12</span>
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
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  </p>
                  <div
                    class="d-row"
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
                      ></i
                      ><span style="color: #ccd4da">12</span>
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
          <div class="d-col3">
            <span>© Copyright 2015 </span>
            <span style="color: #00bcd4">CodexThemes</span>
          </div>
          <div class="d-col6" style="padding: 0 30px">
            <div class="d-row">
              <div class="d-col3" style="border-right: solid 1px #394050;">
                Support
              </div>
              <div class="d-col3" style="border-right: solid 1px #394050;">
                Contact Us
              </div>
              <div class="d-col3" style="border-right: solid 1px #394050;">
                Disclaim
              </div>
              <div class="d-col3">Privacy Policy</div>
            </div>
          </div>
          <div class="d-col3">
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
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss">
footer {
  .foot {
    .d-col3 {
      color: #fff;
      text-align: center;
    }
  }
  padding: 100px 0;

  .d-col3 {
    padding: 0 10px;
  }
  .ft-imgP {
    padding: 40px 0;
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
    padding: 5px 10px;
    background-color: #181828;
    color: #ccd4da;
    border: 1px solid #394050;
  }
  .icon {
    display: inline-block;
    background-color: #394050;
    padding: 5px 10px;
    color: #ccd4da;
    border-radius: 0 5px 5px 0;
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
  }
  background-color: #212331;
}
</style>
