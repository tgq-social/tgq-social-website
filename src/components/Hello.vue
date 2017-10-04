<template>
  <div class="hello">
    <h1>{{ title }}</h1>
    <h2>
      <span class="y">Y</span><span class="o">o</span><span class="u">u</span> Belong
    </h2>
    <ul>
      <li>
        <a class="facebook" href="https://www.facebook.com/TGQSocial/" target="_blank">
          <i class="fa fa-facebook fa-4x" aria-hidden="true"></i><span>Facebook</span>
        </a>
      </li>
      <li>
        <a class="github" href="https://github.com/tgq-social/tgq-social-website" target="_blank">
          <i class="fa fa-github fa-4x" aria-hidden="true"></i><span>GitHub</span>
        </a>
      </li>
      <!-- <li>
        <a href="https://chat.vuejs.org" target="_blank">Community Chat</a>
      </li> -->
    </ul>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      title: 'TGQ Social',
      subtitle: 'You Belong'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello a {
  text-decoration: none;
}

.facebook {
  color: #4267b2;
  font-weight: bold;
}

.github {
  color: #000000;
  font-weight: bold;
}

.y {
  color: black;
  -webkit-text-fill-color: #00a5c6; /* Will override color (regardless of order) */
  -webkit-text-stroke-width: 1px;
  -webkit-text-stroke-color: black;
}

.o {
  color: black;
  -webkit-text-fill-color: white; /* Will override color (regardless of order) */
  -webkit-text-stroke-width: 1px;
  -webkit-text-stroke-color: black;
}

.u {
  color: black;
  -webkit-text-fill-color: #ff309c; /* Will override color (regardless of order) */
  -webkit-text-stroke-width: 1px;
  -webkit-text-stroke-color: black;
}

h1 {
  margin: 0;
  font-size: 150pt;
}

h2 {
  margin: 0;
  font-weight: normal;
  font-size: 100pt;
}

h2 > span {
  padding: 0;
  margin: 0;
}

ul {
  list-style-type: none;
  padding: 50px 0 5px 0;
  font-size: 15pt;
}

li {
  display: inline-block;
  margin: 0 10px;
}
</style>
