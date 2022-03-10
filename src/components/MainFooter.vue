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

          <button>
              SIGN-UP NOW!
          </button>

          <div>
              <span>FOLLOW US</span>
              <ul>
                  <li>Facebook</li>
                  <li>Twitter</li>
                  <li>YouTube</li>
                  <li>Pinterest</li>
                  <li>Maps</li>
              </ul>
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
        padding: 40px 0;
    }

    .container {
        // border: 3px solid rgb(0, 132, 255);
        display: flex;
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
    }

}

</style>