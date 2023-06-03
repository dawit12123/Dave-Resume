<script setup>
import HelloWorld from './components/HelloWorld.vue'
// import Home from './pages/Home'
import Home from './pages/Home/index.vue'
import './assets/js/jquery.min.js'
import './assets/js/bootstrap.min.js'
import './assets/js/smoothscroll.js'
import './assets/js/owl.carousel.min.js'
import './assets/js/custom.js'
import './assets/css/bootstrap.min.css'
import './assets/css/all.min.css'
import './assets/css/owl.carousel.min.css'
import './assets/css/owl.theme.default.min.css'
import './assets/css/tooplate-ben-resume-style.css'
</script>

<template>
  <!-- <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div> -->
  <!-- <HelloWorld msg="Vite + Vue" /> -->
  <Home/>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
