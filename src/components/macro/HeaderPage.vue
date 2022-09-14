<template>
    <div id="app">
        <TopBar></TopBar>
        <SearchBar></SearchBar>
    </div>
  </template>
  
  <script>
import TopBar from '../sections/TopBar.vue';
import SearchBar from '../sections/SearchBar.vue';
  
  
  export default {
    name: 'App',
    components: {
    TopBar,
    SearchBar
}
  }
  </script>
  
  <style lang="scss">
  
  </style>