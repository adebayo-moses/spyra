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
@font-face {
  font-family: "Satoshi";
  src: local("Satoshi-Regular"), url("./assets/fonts/Satoshi-Regular.ttf") format("truetype");
  }

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

@media (max-width: 768px) {
  .sub-paragraph {
    width: 100%;
  }
}

@media (max-width: 768px) {
  header .heading {
  font-size: 70px;
  }
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


video {
  width: 100%;
  height: 80vh;
  object-fit: cover;
  z-index: 1;
}

.video-overlay {
  width: 100%;
  height: 100%;
  position: absolute;
  display: grid;
  place-items: center;
  top: 0;
  left: 0;
  background-color: rgba(0, 0, 0, 0.603);
  z-index: 2;
}

.video-overlay {
  color: white;
  display: grid;
  text-align: center;
  width: 100%;
}


.video-overlay .details h1{
    font-weight: normal;
    font-size: 4.5em;
}

@media (max-width: 768px) {
    .video-overlay .details h1{
        font-size: 2.5em;
}
    }

</style>