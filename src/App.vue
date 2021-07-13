<template>
  <div id="app">
    <Header />
    <Main />
    <Section />
    <Footer />
    <FooterSocialMedia />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Section from './components/Section.vue'
import Footer from './components/Footer.vue'
import FooterSocialMedia from './components/FooterSocialMedia.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Section,
    Footer,
    FooterSocialMedia
  }
}
</script>

<style lang="scss" >
   body{
     background-color: black;
   }
</style>
