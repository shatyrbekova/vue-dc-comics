<template>
  <div id="app">
    <Header  :menuList="menuList"/>
    <Main :comics="comics"  />
    <Section />
    <Footer />
    <FooterSocialMedia />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Section from "./components/Section.vue";
import Footer from "./components/Footer.vue";
import comicsJson from "./jsons/dc-comics.json";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Section,
    Footer
  },
  data: function() {
    return {
      comics: comicsJson,

      menuList: [
        { id: 0, name: "CHARACTERS", link: "/CHARACTERS" },
        { id: 1, name: "COMICS", link: "/COMICS" },
        { id: 2, name: "MOVIES", link: "/MOVIES" },
        { id: 3, name: "TV", link: "/TV" },
        { id: 0, name: "GAMES", link: "/GAMES" },
        { id: 0, name: "COLLECTIBLES", link: "/COLLECTIBLES" },
        { id: 0, name: "VIEDOS", link: "/VIEDOS" },
        { id: 0, name: "FANS", link: "/FANS" },
        { id: 0, name: "NEWS", link: "/NEWS" },
        { id: 0, name: "SHOP", link: "/SHOP" }
      ]
    };
  }
};
</script>

<style lang="scss" >
@import "./style/app.scss";
body {
}
</style>
