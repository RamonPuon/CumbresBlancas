<template>
  <UpperNav/>
  <HomeFirst/>
  <HomeNews/>
</template>

<script>
import UpperNav from './components/UpperNav.vue'
import HomeFirst from './components/HomeFirst.vue'
import HomeNews from './components/HomeNews.vue'

export default {
  name: 'App',
  components: {
    UpperNav,
    HomeFirst,
    HomeNews
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  margin:0;
}
body{
  margin:0;
}
</style>
