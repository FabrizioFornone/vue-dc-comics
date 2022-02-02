<template>
  <main>
    <jumbo-box />
    <cards-box :cardProps="cardList" />
    <merch-box />
  </main>
</template>

<script>
import JumboBox from "./JumboBox.vue";
import CardsBox from "./CardsBox.vue";
import MerchBox from "./MerchBox.vue";

export default {
  components: { JumboBox, CardsBox, MerchBox },
  props: {
    cardList: Array,
  },
};
</script>

<style lang="scss" scoped>
@import "@/style/mainPageStyle.scss";
</style>
