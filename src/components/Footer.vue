<template>
<footer>
     <nav>
      <ul>
      <li><a href="https://github.com/pankaja-shree/" target="_blank">Github</a></li>
      <li><a href="https://in.linkedin.com/in/pankajashree-r-0a2a5167">LinkedIn</a></li>
      <li><a href="https://twitter.com/pankajashree">Twitter</a></li>
      <li><a href="https://medium.com/@pankajashree">Blog</a></li>
      </ul>
    </nav>
    </footer>
</template>

<script>
export default {
  name: 'app-footer'
}
</script>

<style>
footer {
  margin: 0;
  height: 56px;
  padding: 2%;
}

footer nav ul {
  display: flex;
  justify-content: center;
}

footer a {
    color: #000;
    text-decoration: none;
    transition: all 0.5s ease;
}

footer a:hover {
    border-bottom: 2px solid #000;
    cursor: pointer;
}
</style>