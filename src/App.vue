<template>
  <div id="app">
    <header-box />
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
};
</script>

<style lang="scss">
@import "@/style/main.scss";
</style>
