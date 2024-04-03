<template>
  <HeaderMain />
  <RouterView />
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router';
import HeaderMain from './components/HeaderCommon.vue';
</script>

<style scoped>
</style>
