<template>
  <main>
    <jumbo-box />
    <card-box :cardProps="cardList" />
    <merch-box />
  </main>
</template>

<script>
import JumboBox from "./JumboBox.vue";
import CardBox from "./CardsBox.vue";
import MerchBox from "./MerchBox.vue";

export default {
  components: { JumboBox, CardBox, MerchBox },
  props: {
    cardList: Array,
  },
};
</script>

<style lang="scss" scoped>
@import "@/style/mainPageStyle.scss";
</style>
