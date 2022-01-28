<template>
  <main>
    <jumbo-box />
    <card-box :cardProps="cardList" />
  </main>
</template>

<script>
import JumboBox from "./JumboBox.vue";
import CardBox from "./CardsBox.vue";
export default {
  components: { JumboBox, CardBox },
  props: {
    cardList: Array,
  },
};
</script>

<style lang="scss" scoped>
@import "@/style/mainPageStyle.scss";
</style>
