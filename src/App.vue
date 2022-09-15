<template>
  <div id="app">
    <HeaderPage></HeaderPage>
    <MainPage></MainPage>
  </div>
</template>

<script>
import HeaderPage from './components/macro/HeaderPage.vue';
import MainPage from './components/macro/MainPage.vue';

export default {
  name: 'App',
  components: {
    HeaderPage,
    MainPage
}
}
</script>

<style lang="scss">
body {
        margin: 0 auto;
    }
</style>
