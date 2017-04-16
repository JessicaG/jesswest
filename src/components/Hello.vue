<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Hacker</h2>
    <ul>
      <li><a href="http://www.parkifi.com" target="_blank">Engineering Team Lead</a></li>
      <li><a href="http://www.redsson.com" target="_blank">Software Developer</a></li>
      <li><a href="http://www.commercekitchen.com" target="_blank">Software Developer & Marketer</a></li>
    </ul>
    <h2>Hustler</h2>
    <ul>
      <li><a href="http://gocode.colorado.gov/" target="_blank">Go Code Colorado</a></li>
      <li><a href="http://dinosaurjs.org/" target="_blank">DinosaurJS</a></li>
      <li><a href="http://www.joanclarkesociety.com/" target="_blank">Joan Clarke Society</a></li>
    </ul>
    <h2>Socialite</h2>
    <ul>
      <li><a href="http://twitter.com/jessicaewest" target="_blank">Twitter</a></li>
      <li><a href="https://www.linkedin.com/in/jessicagoulding/" target="_blank">LinkedIn</a></li>
      <li><a href="https://jessicag.github.io" target="_blank">Blog</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Jessica Elaine West'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
i
body {
  background-color: #D3D3D3;
}
</style>
