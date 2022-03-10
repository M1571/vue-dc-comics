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
    // border: 5px solid red;
    color: white;
                    
    .footer-main {
        border: 5px solid rgb(255, 145, 0);
        background: url('../assets/img/footer-bg.jpg');
        padding: 40px 0;
    }

    .container {
        border: 5px solid rgb(179, 255, 0);
        display: flex;
    }

    .col {
        border: 5px solid rgb(17, 0, 255);
        width: calc(100% / 9);
    }

    .col-list {
        border: 5px solid rgb(255, 0, 0);
        @include widget;
    }

    li {
        color: #959595;
    }

    // -------------------------------

    .footer-bottom {
        background-color: #303030;
    }

}

</style>