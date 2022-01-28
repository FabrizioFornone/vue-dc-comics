<template>
  <main>
    <jumbo-box />
    <card-box />
  </main>
</template>

<script>
import JumboBox from "./JumboBox.vue";
import CardBox from "./CardsBox.vue";
export default {
  components: { JumboBox, CardBox },
};
</script>

<style lang="scss" scoped>
@import "@/style/mainPageStyle.scss";
</style>
