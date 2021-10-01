<template>
  <footer>
    <div id="footer-top">
      <div class="container">
        <div id="footer-top-left">
          <div id="footer-left1">
            <h2>DC COMICS</h2>
            <ul>
              <li>
                <a href="#">Characters</a>
              </li>
              <li>
                <a href="#">Comics</a>
              </li>
              <li>
                <a href="#">Movies</a>
              </li>
              <li>
                <a href="#">TV</a>
              </li>
              <li>
                <a href="#">Games</a>
              </li>
              <li>
                <a href="#">Videos</a>
              </li>
              <li>
                <a href="#">News</a>
              </li>
            </ul>
            <h2>SHOP</h2>
            <ul>
              <li>
                <a href="#">Shop DC</a>
              </li>
              <li>
                <a href="#">Shop DC Collectibles</a>
              </li>
            </ul>
          </div>
          <div id="footer-left2">
            <h2>DC</h2>
            <ul>
              <li>
                <a href="#">Terms of Use</a>
              </li>
              <li>
                <a href="#">Privacy policy (New)</a>
              </li>
              <li>
                <a href="#">Ad Choices</a>
              </li>
              <li>
                <a href="#">Advertising</a>
              </li>
              <li>
                <a href="#">Jobs</a>
              </li>
              <li>
                <a href="#">Subscriptions</a>
              </li>
              <li>
                <a href="#">Talent Workshops</a>
              </li>
              <li>
                <a href="#">CPSC Certificates</a>
              </li>
              <li>
                <a href="#">Ratings</a>
              </li>
              <li>
                <a href="#">Shop Help</a>
              </li>
              <li>
                <a href="#">Contact Us</a>
              </li>
            </ul>
          </div>
          <div id="footer-left3">
            <h2>SITES</h2>
            <ul>
              <li>
                <a href="#">DC</a>
              </li>
              <li>
                <a href="#">MAD Magazine</a>
              </li>
              <li>
                <a href="#">DC Kids</a>
              </li>
              <li>
                <a href="#">DC Universe</a>
              </li>
              <li>
                <a href="#">DC Power Visa</a>
              </li>
            </ul>
          </div>
        </div>
        <div id="footer-top-right">
          <img src="../assets/images/dc-logo-bg.png" alt="" />
        </div>
      </div>
    </div>
    <div id="footer-bottom">
      <div class="container">
        <div id="footer-bottom-left">
          <a id="sign-up" href="#">SIGN-UP NOW!</a>
        </div>
        <div id="footer-bottom-right">
          <ul>
            <li>
              <a id="follow-us" href="#">FOLLOW US</a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/images/footer-facebook.png" alt="">
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/images/footer-twitter.png" alt="">
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/images/footer-youtube.png" alt="">
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/images/footer-pinterest.png" alt="">
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/images/footer-periscope.png" alt="">
              </a>
            </li>

          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>
  
<style lang="scss" scoped>
@import "../assets/style/variables";
footer {
  height: 30rem;
}

#footer-top {
  height: 23.125rem;
  background-image: url(../assets/images/footer-bg.jpg);
  .container {
    display: flex;
    justify-content: space-between;
    ul {
      list-style: none;
      a {
        text-decoration: none;
        color: $lighterGrey;
      }
    }
  }
}
#footer-top-left {
  display: flex;
  h2 {
    color: white;
    padding: .625rem 0;
  }
  #footer-left1,
  #footer-left2,
  #footer-left3 {
    display: flex;
    flex-direction: column;
    padding-top: 2.5rem;
    margin-right: 3.125rem;
  }
}

#footer-top-right {
  display: flex;
  align-items: center;
  overflow: hidden;
  img {
    width: 155%;
    height: 150%;
  }
}

#footer-bottom {
  height: 6.875rem;
  background-color: $lightGrey;
  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  #sign-up {
    background-color: transparent;
    border: .0625rem solid $blue;
    color: white;
    font-weight: 500;
    font-size: 1.125rem;
    padding: .625rem .9375rem;
    text-decoration: none;
  }
  ul {
    list-style: none;
    display: flex;
    align-items: center;
    a {
      color: white;
      text-decoration: none;
      padding: 0 .9375rem;
    }
  }
  #follow-us {
    font-size: 1.375rem;
    font-weight: bold;
    color: $blue;
  }
}
</style>