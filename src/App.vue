<template>
  <div id="app">
    <Header/>
    <Cards/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Cards from './components/Cards.vue';
import Footer from './components/Footer.vue';
export default {
  name: 'App',
  components: {
    Header,
    Cards,
    Footer,
  }
}
</script>

<style lang="scss">
@import './assets/style/common.scss';

</style>
