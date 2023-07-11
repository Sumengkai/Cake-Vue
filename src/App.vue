<script setup>
import headerView from "./components/Header.vue";
import homeView from "./components/HomeView.vue";
import onSealView from "./components/OnSealView.vue";
import footerArea from "./components/footer.vue";
</script>

<template>
  <div class="app-wrapper">
    <headerView />
    <homeView />
    <onSealView />
    <footerArea />
  </div>
</template>

<style lang="scss" scoped>
.app-wrapper {
  margin: 0 auto;
  width: 90%;
  background-color: bisque;
}
</style>
