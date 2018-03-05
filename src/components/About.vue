<template>
  <div class="hello">
    <h2>{{ title }}</h2>
    <p v-html="aboutPara"></p>
    <p v-html="interestsPara"></p>
    <p v-html="skillsPara"></p>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      title: 'About Me',
      aboutPara: 'I am an Electrical Engineering Graduate (2015 batch) from R. V. College of Engineering, Bangalore with 2 years of experience working as a research associate in <a href = "http://samskrti.org/">Samskrti Foundation</a>, a private research and development NGO, helping them build web applications, digital repositories, preparing presentations for seminars and conferences, project proposals and design of quarterly newsletters of the organisation.',
      skillsPara: '<em>Skills</em>: Responsive Web design using HTML, CSS3 and Javascript, Data visualization using Python and Javascript, Machine learning using Python and Tensor Flow, Audio and Video editing and compilation and Graphic design using Adobe InDesign.',
      interestsPara: '<em>Interests:</em> Research related to Indian knowledge systems and Philosophical schools, Indian Carnatic Music, Natural language processing as applied to Indian languages'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
p {
  padding: 0 8%;
  line-height: 1.8;
  text-align: justify;
}

p a {
  color: #005cb2;
  text-decoration: none;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

</style>
