<template>
  <div class="relative-parent">
    <h2>Current Series</h2>
    <div class="card-row container d-flex">
      <div class="card-box" v-for="(card, index) in cardProps" :key="index">
        <div class="single-card">
          <a href="#">
            <img :src="card.thumb" alt="" />
          </a>
        </div>
          <h4>{{ card.series }}</h4>
      </div>
    </div>
    <div class="d-flex justify-content-center">
      <button class="pointer"><a href="#">LOAD MORE</a></button>
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
@import "@/style/cardsStyle.scss";
</style>
