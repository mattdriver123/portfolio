<template>
  <div id="app">
    <section>
      <h1>Matthew Driver</h1>
      <p><i>
        About Me
      </i></p>
    </section>
    <section>
      <h2>Skills</h2>
      <ul style="list-style: none; padding: 0;">
        <li>HTML</li>
        <li>CSS</li>
        <li>JS</li>
        <li>Bootstrap</li>
        <li>jQuery</li>
        <li>Node.js</li>
        <li>Webpack</li>
        <li>Vue.js</li>
        <li>Python</li>
        <li>Flask</li>
        <li>Jinja2</li>
        <li>Nginx</li>
        <li>Docker</li>
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
      <div>Email: <a href="mailto:matt@mattdriver.me.uk">matt@mattdriver.me.uk</a></div>
      <div>Github: <a href="https://github.com/mattdriver123" target="_blank">https://github.com/mattdriver123</a></div>
      <div>LinkedIn: <a href="https://www.linkedin.com/in/matthew-driver" target="_blank">https://www.linkedin.com/in/matthew-driver</a></div>
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
  max-width: 800px;
  margin: 0 auto;
}
</style>
