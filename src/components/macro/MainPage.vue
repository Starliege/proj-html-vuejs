<template>
    <div id="app">
        <PostJumbo></PostJumbo>
        <UnlimitedLearning></UnlimitedLearning>
        <RecentCourses></RecentCourses>
    </div>
  </template>
  
  <script>
import PostJumbo from '../sections/PostJumbo.vue';
import UnlimitedLearning from '../sections/UnlimitedLearning.vue';
import RecentCourses from '../sections/RecentCourses.vue';


  export default {
    name: 'App',
    components: {
    PostJumbo,
    UnlimitedLearning,
    RecentCourses
},
}
  </script>
  
  <style lang="scss">
  
  </style>