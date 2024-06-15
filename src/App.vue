<template>
  <div id="app">
    <SiteHeader />
    <HomePage />
  </div>
</template>

<script>
import SiteHeader from './components/SiteHeader.vue';
import HomePage from './views/HomePage.vue';

export default {
  name: 'App',
  components: {
    SiteHeader,
    HomePage
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
