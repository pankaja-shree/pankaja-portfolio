<template>
  <div id="app">
    <AppHeader />
    <main>
      <!--<img src="./assets/logo.png" alt="Vue.js PWA">-->
      <router-view></router-view>
    </main>
  </div>
</template>

<script>
import AppHeader from '@/components/Header'
export default {
  name: 'app',
  components: {
    AppHeader
  }
}
</script>

<style>
body {
  margin: 0;
  font-weight: lighter;
  letter-spacing: 2px;
  word-spacing: 10px;
}

#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

main {
  text-align: center;
  margin-top: 40px;
}

</style>
