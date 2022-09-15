<template>
  <div id="app">
    <HeaderPage></HeaderPage>
    <MainPage></MainPage>
    <FooterPage></FooterPage>
  </div>
</template>

<script>
import HeaderPage from './components/macro/HeaderPage.vue';
import MainPage from './components/macro/MainPage.vue';
import FooterPage from './components/macro/FooterPage.vue';

export default {
  name: 'App',
  components: {
    HeaderPage,
    MainPage,
    FooterPage
}
}
</script>

<style lang="scss">
body {
        margin: 0 auto;
    }
</style>
