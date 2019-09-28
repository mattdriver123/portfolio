<template>
  <div id="app">
    <section>
      <h1 style="font-size: 3rem; margin-bottom: 24px;">Matthew Driver</h1>
      <p><i>
        Professional web developer with a master's degree in computing and 4+ years experience in a fast-growing agile startup.
      </i></p>
    </section>
    <section>
      <h2>Skills</h2>
      <ul class="pills">
        <li class="pill">HTML5</li>
        <li class="pill">CSS3</li>
        <li class="pill">JavaScript</li>
        <li class="pill">Bootstrap 3</li>
        <li class="pill">jQuery</li>
        <li class="pill">Node.js</li>
        <li class="pill">Webpack</li>
        <li class="pill">Vue.js</li>
        <li class="pill">Python</li>
        <li class="pill">Flask</li>
        <li class="pill">Jinja2</li>
        <li class="pill">Nginx</li>
        <li class="pill">Docker</li>
      </ul>
    </section>
    <section>
      <h2>Experience</h2>
      <h3>Egress Software Technologies</h3>
      <h4>Sep 2016 - Present - Software Developer</h4>
      <h4>Jan 2016 - Sep 2016 - UI/UX Developer</h4>
      <h4>Feb 2015 - Jan 2016 - QA Engineer</h4>
      <h3>Sheffield Hallam University</h3>
      <h4>Nov 2013 - May 2014 - Computer Programming Mentor</h4>
    </section>
    <section>
      <h2>Contact</h2>
      <a class="icon-circle" href="mailto:matt@mattdriver.me.uk">
        <i class="fa fa-envelope fa-2x"></i>
      </a>
      <a class="icon-circle" href="https://github.com/mattdriver123" target="_blank">
        <i class="fa fa-github fa-inverse fa-2x"></i>
      </a>
      <a class="icon-circle" href="https://www.linkedin.com/in/matthew-driver" target="_blank">
        <i class="fa fa-linkedin fa-2x"></i>
      </a>
    </section>
    <section>
      <p>This site was designed and built by me, using Vue.js</p>
    </section>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
body {
  padding: 0;
  margin: 0;

  font-size: 1.2rem;
  font-weight: 300;
  font-family: 'Montserrat', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
#app {
  text-align: center;
}
#app h2 {
  margin-bottom: 24px;
}
#app .pills {
  list-style: none;
  padding: 0;
  width: 50%;
}
#app .pills .pill {
  display: inline-block;
  padding: 4px 10px;
  background: #444;
  margin: 4px;
  border-radius: 4px;
}
#app .icon-circle {
  background: #444;
  color: white;
  width: 70px;
  height: 70px;
  border-radius: 50%;
  line-height: 83px;
  text-align: center;
  display: inline-block;
  margin: 0 15px;
}
#app .icon-circle:hover {
  background: #555;
}
section {
  padding: 100px;
}
section:nth-child(odd) {
  color: #444;
  background-color: white;
}
section:nth-child(even) {
  color: #fff;
  background-color: teal;
  box-shadow: inset 0 0 15px rgba(0, 0, 0, 0.15);
}
section > * {
  max-width: 900px;
  margin: 0 auto;
}
</style>
