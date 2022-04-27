<script setup>
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <title>Spyro</title>
    <img alt="spyra logo" class="logo" src="./assets/logo.png" width="125" height="125" />

    <div class="wrapper">
    </div>

    <div class="mt-5 mb-5">
      <!-- <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/contact">Contact</router-link> -->
      </div>
      <p class="heading">Spyra</p>
      <p class="sub-heading">A simple, fast and secure way to share files with your friends.</p>
      <p class="sub-paragraph">Spyra is a free, entirely remote, four-month-long immersive programme for helping Startups refine their business model and help prepare them for investment readiness.</p>
<div>
  <!-- <a href="https://spyra.co/"> -->
    <!-- <img style="height: 100px; width: 100px;" src="./assets/logo.png" alt="spyra logo">  </a> -->
    </div>
    </header>

    <!-----------Video Intro---------->
  <main class="bg-video-wrap mb-8">
<video src="./assets/video/video.mp4" autoplay loop muted ></video>
<div class="video-overlay">
  <div class="details">
    <h1>Growth is Essential</h1>
  </div>
</div>
  </main>
</template>

<style>
@import './assets/base.css';

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;
  font-weight: normal;
}

.title {
  font-style: normal;
  font-weight: normal;
  font-size: 25pc;
  line-height: 37px;
  letter-spacing: 0.3rem;
  text-transform: uppercase;
  margin-bottom: 2em;
  width: 100%;
  text-align: center;
}

header {
  display: grid;
  place-items: center;
  width: 100%;
  margin-bottom: 190px;
}

header .heading {
  font-style: normal;
  font-weight: norbomal;
  font-size: 190px;
  line-height: 1;
  padding-bottom: 30px;
  text-align: center;
  letter-spacing: 0.05em;
  margin-bottom: 25px;
}

.sub-heading {
  font-style: normal;
  font-weight: normal;
  font-size: 30px;
  line-height: 45px;
  text-align: center;
  /* color: #ffffff; */
  margin-bottom: 11px;
}

.sub-paragraph {
  width: 669px;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  text-align: center;
  /* color: #000000; */
  margin-bottom: 44px;
}

</style>
