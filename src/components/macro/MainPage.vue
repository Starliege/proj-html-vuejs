<template>
    <div id="app">
        <PostJumbo></PostJumbo>
        <UnlimitedLearning></UnlimitedLearning>
        <RecentCourses></RecentCourses>
        <NewsLetter></NewsLetter>
        <PopularCourses></PopularCourses>
        <InstructorBusiness></InstructorBusiness>
        <InvestingFuture></InvestingFuture>
    </div>
  </template>
  
  <script>
import PostJumbo from '../sections/PostJumbo.vue';
import UnlimitedLearning from '../sections/UnlimitedLearning.vue';
import RecentCourses from '../sections/RecentCourses.vue';
import NewsLetter from '../sections/NewsLetter.vue';
import PopularCourses from '../sections/PopularCourses.vue';
import InstructorBusiness from '../sections/InstructorBusiness.vue';
import InvestingFuture from '../sections/InvestingFuture.vue';


  export default {
    name: 'App',
    components: {
    PostJumbo,
    UnlimitedLearning,
    RecentCourses,
    NewsLetter,
    PopularCourses,
    InstructorBusiness,
    InvestingFuture
},
}
  </script>
  
  <style lang="scss">
  
  </style>