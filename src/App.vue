<template>
  <div id="app">
    <header-box :menu="nav" />
    <main-box />
    <merch-box />
    <footer-box />
    <second-footer-box />
  </div>
</template>

<script>
import HeaderBox from "./components/HeaderBox.vue";
import MainBox from "./components/MainBox.vue";
import MerchBox from "./components/MerchBox.vue";
import FooterBox from "./components/FooterBox.vue";
import SecondFooterBox from "./components/SecondFooterBox.vue";
export default {
  name: "App",
  components: {
    HeaderBox,
    MainBox,
    MerchBox,
    FooterBox,
    SecondFooterBox,
  },
  data() {
    return {
      nav: [
        {
          id: "0452726435",
          label: "CHARACTERS",
          url: "/",
        },
        {
          id: "1452726436",
          label: "COMICS",
          url: "/",
        },
        {
          id: "2452726437",
          label: "MOVIES",
          url: "/",
        },
        {
          id: "3452726438",
          label: "GAMES",
          url: "/",
        },
        {
          id: "4452726439",
          label: "COLLECTIBLES",
          url: "/",
        },
        {
          id: "5452726440",
          label: "VIDEOS",
          url: "/",
        },
        {
          id: "6452726441",
          label: "FANS",
          url: "/",
        },
        {
          id: "7452726442",
          label: "NEWS",
          url: "/",
        },
        {
          id: "8452726443",
          label: "SHOP",
          url: "/",
        },
      ],
    };
  },
};
</script>

<style lang="scss">
@import "@/style/main.scss";
</style>
