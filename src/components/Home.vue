<template>
  <div class="home">
    <p>{{ introPara }}</p>
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      introPara: "I'm Pankajashree, a web developer from Mysore. I have been building mobile first, progressive web applications that is accessible to all using Javascript and Python since 2 years."
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
p {
  padding: 8%;
  font-size: 1.5em;
  line-height: 2;
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
  color: #35495E;
}
</style>
