<template>
  <div class="card-box">
    <div v-for="(card, index) in cardProps" :key="index">
      <img :src="card.thumb" alt="" />
      <h3>{{ card.series }}</h3>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    cardProps: Array,
  },
};
</script>

<style lang="scss" scoped>
@import "@/style/cardStyle.scss";
</style>
