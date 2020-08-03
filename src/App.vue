<template>
  <div id="app">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <NavBar/>

  </div>
</template>

<script>

import NavBar from './components/NavBar';


export default {
  name: 'App',

  components: {
    NavBar,
  },


};
</script>

<style>
  * {
      margin: 0;
      padding: 0;
    }
</style>