<template>
  <div class="relative-parent">
    <h2>Current Series</h2>
    <div class="card-box container d-flex">
      <div class="single-card" v-for="(card, index) in cardProps" :key="index">
        <img :src="card.thumb" alt="" />
        <h3>{{ card.series }}</h3>
      </div>
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
