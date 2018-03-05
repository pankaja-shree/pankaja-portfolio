<template>
  <div class="hello">
    <h1>{{ title }}</h1>
    <p>{{ aboutPara }}</p>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      title: 'About',
      aboutPara: "I'm Pankajashree, a web developer from Mysore. I have worked for 2 years in a research and development NGO, helping build web applications, digital repositories and assist in content management for preparing seminar presentations, project proposals and design of quarterly newsletters of the organisation. My skills include: Responsive Web design, Data visualization, Machine learning using Tensor Flow, Audio and Video editing and compilation."
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
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
  color: #35495E;
}
</style>
