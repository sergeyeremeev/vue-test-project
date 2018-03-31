<template>
  <div id="app">
    <Header/>
  </div>
</template>

<script>
import Header from './components/header/SiteHeader';

export default {
  name: 'App',
  components: {
    Header,
  },
};
</script>

<style>
  body {
    margin: 0;
    padding: 0;
  }

  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  a {
    color: inherit;
    text-decoration: none;
  }
</style>
