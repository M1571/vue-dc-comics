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
                            <li>link 1</li>
                            <li>link 2</li>
                            <li>link 3</li>
                        </ul>

                  </div>
              </div>

              <div class="col">
                  <div class="col-list">

                        <h4 class="list_title">DC</h4>
                        <ul class="list_menu">
                            <li>link 1</li>
                            <li>link 2</li>
                            <li>link 3</li>
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

    color: white;

    .footer-main {
        background: url('../assets/img/footer-bg.jpg');
        padding: 40px 0;

        .container {
            display: flex;

            .col {
                width: calc(100% / 9);

                col-list {
                    @include widget;

                    .list_title {
                        color: white;
                    }

                    li {
                        color: #959595;
                    }
                }
            }
        }
    }

    // -------------------------------

    .footer-bottom {
        background-color: #303030;
    }

}

</style>