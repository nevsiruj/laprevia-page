<template>
  <div id="app">
    <Header />
    <Banner />
    <Services />
    <!-- <Portfolio /> -->
    <Ubicaciones />

    <!-- <AboutSection /> -->
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Banner from './components/Banner.vue';
import Portfolio from './components/Portfolio.vue';
import Services from './components/Services.vue';
import Ubicaciones from './components/Ubicaciones.vue';
import AboutSection from './components/AboutSection.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Banner,
    Services,
    Portfolio,
    Ubicaciones,
    AboutSection,
    Footer,
  },
};
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
