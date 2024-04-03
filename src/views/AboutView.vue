<template>
  <div class="common_title_bg">
      <h3 class="main_heading">About</h3>
  </div>
  <AboutInfoDetails />
  <TeamMeet />
</template>

<script setup>
import AboutInfoDetails from '../components/about/AboutInfoDetails.vue'
import TeamMeet from '../components/about/TeamMeet.vue'
</script>

<style lang="scss">
@import '../assets/scss/aboutPage.scss';
</style>