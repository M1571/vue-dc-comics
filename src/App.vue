// -------------------------------
// HTML

<template>

  <div id="app">
    <Header />
    <Main />
    <Footer />
  </div>

</template>

// -------------------------------
// JS

<script>

import Header from './components/MainHeader.vue'
import Main from './components/MainContent.vue'
import Footer from './components/MainFooter.vue'

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer
  },
};

</script>

// -------------------------------
// CSS
 
<style lang="scss">

@import './assets/scss/mixins.scss';

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
} 

img {
  max-width: 100%;
}

a {
  text-decoration: none; 
  color: currentColor;
}

ol, ul {
  list-style: none;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.container {
  @include container;
}

</style>
