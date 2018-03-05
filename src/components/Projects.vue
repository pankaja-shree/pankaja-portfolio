<template>
  <div class="projects">
    <h2>{{ title }}</h2>
    <ul>
      <h3>Research Papers</h3>
      <li>Jnanashwatha - Knowledge Tree</li>
      <h3>Chatbots - Tech stack: NodeJS, ExpressJS</h3>
      <li><a href="https://pankaja-shree.github.io/sns-splash/">Slack bot</a> - To manage private channels on the Slack app.</li>
      <li><a href="https://pankaja-shree.github.io/wiki-bot/">Facebook Messenger bot</a> - A bot to browse the Wikipedia website from facebook messenger app.</li>
      <h3>Websites - Tech stack: HTML5, CSS3, Javascript </h3>
      <li><a href="https://pankaja-shree.github.io/ayurveda-frontpage/">Landing page design for Ayurveda Digital Repository</a></li>
      <li><a href="http://nice-turn.surge.sh/">Random Quote Generator</a></li>
      <li><a href="http://staking-calculator.surge.sh/">Wikipedia Viewer</a></li>
      <li><a href="http://waggish-comb.surge.sh/">Calculator App</a></li>
      <li><a href="http://fearless-class.surge.sh/">Pomodoro Timer App</a></li>
      <li><a href="http://better-seed.surge.sh/">Tic Tac Toe Game using MinMax Algorithm</a></li>
      <li><a href="http://recipefcc.surge.sh/">Recipe Diary App</a></li>
    </ul>
    Visit my Github profile and blog to know more about all my projects.
  </div>
</template>

<script>
export default {
  name: 'projects',
  data () {
    return {
      title: 'My Work'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

ul {
  list-style-type: none;
  padding: 0 5%;
  text-align: left;
}

li {
  margin: 0 10px;
  line-height: 1.3em;
}

a {
  color: #35495E;
}
</style>
