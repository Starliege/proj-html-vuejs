<template>
    <div id="app">
        <PostJumbo></PostJumbo>
        <UnlimitedLearning></UnlimitedLearning>
        <RecentCourses></RecentCourses>
        <NewsLetter></NewsLetter>
    </div>
  </template>
  
  <script>
import PostJumbo from '../sections/PostJumbo.vue';
import UnlimitedLearning from '../sections/UnlimitedLearning.vue';
import RecentCourses from '../sections/RecentCourses.vue';
import NewsLetter from '../sections/NewsLetter.vue';


  export default {
    name: 'App',
    components: {
    PostJumbo,
    UnlimitedLearning,
    RecentCourses,
    NewsLetter
},
}
  </script>
  
  <style lang="scss">
  
  </style>