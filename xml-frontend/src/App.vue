<template>
  <div id="app">
   <ad-page></ad-page>
   <router-view />
  </div>
</template>

<script>
import NewAd from './components/NewAd.vue'

export default {
  name: 'App',
  components: {
    "ad-page" : NewAd
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
}
</style>
