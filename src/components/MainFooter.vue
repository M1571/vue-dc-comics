// -------------------------------
// HTML

<template>

  <footer class="footer">

      <!-- ------------------------------- -->

      <section class="footer-main">

          <div class="container">

              <div class="col">
                  <div class="col-list">

                        <h4 class="list_title">DC Comics</h4>
                        <ul class="list_menu">
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>

                        <h4 class="list_title shop_title">SHOP</h4>
                        <ul class="list_menu">
                            <li>Shop DC</li>
                            <li>Shop Collectibles</li>
                        </ul>

                  </div>
              </div>

              <div class="col">
                  <div class="col-list">

                        <h4 class="list_title">DC</h4>
                        <ul class="list_menu">
                            <li>Terms of Use</li>
                            <li>Privacy policy (New)</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Subscriptions</li>
                            <li>Talent Workshop</li>
                            <li>CPSC Certificates</li>
                            <li>Ratings</li>
                            <li>Shop Help</li>
                            <li>Contact Us</li>
                        </ul>

                  </div>
              </div>

              <div class="col">
                  <div class="col-list">

                        <h4 class="list_title">SITES</h4>
                        <ul class="list_menu">
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>

                  </div>
              </div>

          </div>
          
      </section>

      <!-- ------------------------------- -->

      <section class="footer-bottom">

          <div class="container-bottom">

            <button class="sign-up">
                SIGN-UP NOW!
            </button>

            <div class="follow-us">
                <span>FOLLOW US</span>
                <ul>
                    <li>
                        <img src="../assets/img/footer-facebook.png" alt="Facebook">
                    </li>
                    <li>
                        <img src="../assets/img/footer-twitter.png" alt="Twitter">
                    </li>
                    <li>
                        <img src="../assets/img/footer-youtube.png" alt="YouTube">
                    </li>
                    <li>
                        <img src="../assets/img/footer-pinterest.png" alt="Pinterest">
                    </li>
                    <li>
                        <img src="../assets/img/footer-periscope.png" alt="Maps">
                    </li>
                </ul>
            </div>

          </div>

      </section>

      <!-- ------------------------------- -->

  </footer>

</template>

// -------------------------------
// JS

<script>

export default {

};

</script>

// -------------------------------
// CSS

<style lang="scss" scoped>

@import '../assets/scss/mixins.scss';

.footer {
    // border: 5px solid red;
    color: white;
                    
    .footer-main {
        // border: 3px solid rgb(255, 145, 0);
        background: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
    }

    .container {
        // border: 3px solid rgb(0, 132, 255);
        padding: 40px 0;
        display: flex;
        background: url('../assets/img/dc-logo-bg.png');
        background-repeat: no-repeat;
        background-position: right center;
    }

    .col {
        // border: 3px solid rgb(0, 255, 115);
        width: calc(100% / 9);
    }

    .col-list {
        // border: 3px solid rgb(255, 0, 0);
        @include widget;
    }

    .list_title {
        color: white;
    }

    .shop_title {
        margin-top: 10px;
    }

    li {
        color: #959595;
        font-size: 0.9em;
    }

    // -------------------------------

    .footer-bottom {
        // border: 3px solid rgb(0, 255, 13);
        background-color: #303030;
        padding: 20px 0;
    }

    .container-bottom {
        @include container;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .sign-up {
        border: 3px solid #0086FE;
        padding: 8px;
        font-weight: 800;
        background: transparent;
        color: white;
    }

    .follow-us {
        display: flex;
        gap: 15px;
        align-items: center;
        color: #0086FE;
        font-weight: 800;

        ul {
            display: contents;
        }
    }

}

</style>