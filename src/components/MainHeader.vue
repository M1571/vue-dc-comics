// -------------------------------
// HTML

<template>

  <header class="main-header">

      <div class="container">

          <!-- ------------------------------- -->

          <figure class="logo">
              <img src="../assets/img/dc-logo.png" alt="">
          </figure>

          <!-- ------------------------------- -->

          <nav class="main-nav">

              <ul>
                  <li class="nav-item">
                      <a href="#">CHARACTERS</a>
                  </li>
                  <li class="nav-item active">
                      <a href="#">COMICS</a>
                  </li>
                  <li class="nav-item">
                      <a href="#">MOVIES</a>
                  </li>
                  <li class="nav-item">
                      <a href="#">TV</a>
                  </li>
                  <li class="nav-item">
                      <a href="#">GAMES</a>
                  </li>
                  <li class="nav-item">
                      <a href="#">COLLECTIBLES</a>
                  </li>
                  <li class="nav-item">
                      <a href="#">VIDEOS</a>
                  </li>
                  <li class="nav-item">
                      <a href="#">FANS</a>
                  </li>
                  <li class="nav-item">
                      <a href="#">NEWS</a>
                  </li>
                  <li class="nav-item">
                      <a href="#">SHOP</a>
                  </li>
              </ul>

          </nav>

          <!-- ------------------------------- -->

      </div>

  </header>

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

.main-header {

    // color: #000012;

    .container {
        display: flex;
        justify-content: space-between;
        min-height: 120px;
    }

    // -------------------------------

    .logo {
        align-self: center;

        img {
            display: block;
        }
    }
}

</style>