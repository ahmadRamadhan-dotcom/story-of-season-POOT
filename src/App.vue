<template>
  <Header />
  <main>
    <BannerHero />
    <AvailableNow />
    <Overview />
  </main>
</template>

<script setup>
import Header from "./components/Header.vue";
import BannerHero from "./components/BannerHero.vue";
import AvailableNow from "./components/AvailableNow.vue";
import Overview from "./components/Overview.vue";
</script>
