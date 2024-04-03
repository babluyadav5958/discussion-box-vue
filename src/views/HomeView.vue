<template>
  <HomeHeroBanner />
  <HomeMarquee class="desk_view" />
  <HomeInfoBox />
  <HomeMarquee class="mob_view" />
</template>

<script setup>
import HomeMarquee from '../components/HomeMarquee.vue';
import HomeInfoBox from '../components/HomeInfoBox.vue';
import HomeHeroBanner from '../components/HomeHeroSection.vue';
</script>

<style lang="scss">

</style>