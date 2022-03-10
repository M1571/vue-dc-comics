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
                  <li v-for="(link,i) in links" :key="i" class="nav-item" :class="link.active ? 'active' : '' ">
                      <a href="#">{{ link.text }}</a>
                  </li>
                  <!-- <li class="nav-item active">
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
                  </li> -->
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
    data() {
        return {
            links: [
                {
                    text: 'Characters',
                    href: '#'
                },
                {
                    text: 'Comics',
                    href: '#',
                    active: true
                },
                {
                    text: 'Movies',
                    href: '#'
                },
                {
                    text: 'Tv',
                    href: '#'
                },
                {
                    text: 'Games',
                    href: '#'
                },
                {
                    text: 'Collectibles',
                    href: '#'
                },
                {
                    text: 'Videos',
                    href: '#'
                },
                {
                    text: 'Fans',
                    href: '#'
                },
                {
                    text: 'News',
                    href: '#'
                },
                {
                    text: 'Shop',
                    href: '#'
                },
            ]
        }
    }
};

</script>

// -------------------------------
// CSS

<style lang="scss" scoped>

.main-header {

    // color: #000012;

    .container {
        // border: 3px solid rgb(255, 145, 0);
        display: flex;
        justify-content: space-between;
        min-height: 120px;
    }

    // -------------------------------

    .logo {
        // border: 3px solid rgb(0, 255, 55);
        align-self: center;

        img {
            display: block;
        }
    }

    .main-nav {
        // border: 3px solid rgb(255, 0, 179);
        display: flex;
        gap: 30px;

        ul {
            display: contents;
        }

        .nav-item {
            // border: 3px solid rgb(0, 195, 255);
            font-weight: 800;
            text-transform: uppercase;

            a {
                // border: 5px solid red;
                display: flex;
                align-items: center;
                height: 100%;
            }

            // .&.active, {
                
            //     a::after {
            //         background-color: #0282F9;
            //         content: '';
            //         display: block;
            //         height: 4px;
            //         position: absolute;
            //         left: 0;
            //         bottom: 0;
            //         right: 0;
            //     }
            // }
        }
    }
}

</style>