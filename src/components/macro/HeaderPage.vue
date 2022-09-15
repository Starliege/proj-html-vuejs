<template>
    <div id="app">
        <TopBar></TopBar>
        <SearchBar></SearchBar>
        <ChoiceBar></ChoiceBar>
        <JumboThing></JumboThing>
    </div>
  </template>
  
  <script>
import TopBar from '../sections/TopBar.vue';
import SearchBar from '../sections/SearchBar.vue';
import ChoiceBar from '../sections/ChoiceBar.vue';
import JumboThing from '../sections/JumboThing.vue';

  export default {
    name: 'HeaderPage',
    components: {
    TopBar,
    SearchBar,
    ChoiceBar,
    JumboThing
  },
}
  </script>
  
  <style lang="scss">
  
  </style>