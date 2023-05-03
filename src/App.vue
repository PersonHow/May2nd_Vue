<script setup>
import HeaderView from "./components/views/HeaderView.vue";
import FooterView from "./components/views/FooterView.vue";
import HomeView from "./components/views/HomeView.vue";
</script>

<template>
  <main class="mainArea">
    <HeaderView />
    <HomeView />
    <FooterView />
  </main>
</template>

<style scoped>
.mainArea{
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: space-between;
  flex-direction: column;
}
</style>
