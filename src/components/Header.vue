<template>
<header>
     <nav>
      <ul>
      <li><router-link to='/'>Pankajashree R</router-link></li>
      <li><router-link to='/about'>About</router-link> | <router-link to='/projects'>Work</router-link></li>
      <li>Resume</li>
      </ul>
    </nav>
    </header>
</template>

<script>
export default {
  name: 'app-header'
}
</script>

<style>
header {
  margin: 0;
  height: 56px;
  padding: 2%;
}

nav ul {
  display: flex;
  justify-content: space-between;
}

header a {
    color: #000;
    text-decoration: none;
    transition: all 0.5s ease;
}

header a:hover {
    font-weight: bold;
    font-size: 1.1em;
}
</style>