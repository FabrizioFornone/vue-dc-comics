<template>
  <div id="app">
    <header-box />
    <main-box />
    <merch-box />
  </div>
</template>

<script>
import HeaderBox from "./components/HeaderBox.vue";
import MainBox from "./components/MainBox.vue";
import MerchBox from "./components/MerchBox.vue";
export default {
  name: "App",
  components: {
    HeaderBox,
    MainBox,
    MerchBox,
  },
};
</script>

<style lang="scss">
@import "@/style/main.scss";
</style>
