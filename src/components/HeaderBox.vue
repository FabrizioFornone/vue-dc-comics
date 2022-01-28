<template>
  <header class="d-flex justify-content-between align-items-center container">
    <div>
      <img src="@/assets/img/dc-logo.png" alt="" />
    </div>
    <ul class="d-flex pointer">
      <li class="d-flex align-items-center" v-for="menuItem in menu" :key="menuItem.id">
          <a href="menuItem.url">{{ menuItem.label }}</a>
        </li>
    </ul>
  </header>
</template>

<script>
export default {
   props: {
    menu: Array, 
  },
};
</script>

<style lang="scss" scoped>
@import "@/style/headerStyle.scss";
</style>
