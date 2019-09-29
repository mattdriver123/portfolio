<template>
  <div class="hero-screen">
    <h1>Hello World<span style="color: teal;">.</span></h1>
    <h2>
      I am <b style="color: teal;">Matthew Driver</b>; A professional web developer with a master's degree in computing, a passion for web development,
      and 4+ years experience in a fast-growing agile startup. <b class="blinker">|</b>
    </h2>
    <div class="icon-circle scroll-hint">
      <i class="fa fa-arrow-down fa-2x"></i>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeroScreen",

}
</script>

<style scoped>
.hero-screen {
  width: 100%;
  height: 90%;
  padding: 6% 6% 6% 20%;
  position: relative;
}
.hero-screen:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(#333, #111);
  z-index: -1;
}
.hero-screen h1 {
  font-size: 15vmin;
  font-weight: bold;
  margin: 0;
  color: #fefefe;
  text-shadow: 5px 5px rgba(0, 0, 0, 0.15);
}
.hero-screen h2 {
  font-size: 4vmin;
  font-weight: lighter;
  margin: 0;
  color: #e0e0e0;
  text-shadow: 5px 5px rgba(0, 0, 0, 0.15);
}
.hero-screen > .scroll-hint {
  position: absolute;
  bottom: -35px;
  left: calc(50% - 35px);
  background: white !important;
  color: #333 !important;
}
</style>

<style>
.blinker {
  opacity: 1;
  animation: blinker 1.2s linear infinite;
}
@keyframes blinker {
  0% {
    opacity: 1;
  }
  45% {
    opacity: 1;
  }
  50% {
    opacity: 0;
  }
  95% {
    opacity: 0;
  }
}
</style>
