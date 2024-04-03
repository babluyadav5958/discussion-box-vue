<template>
    <HeaderMain />
    <router-view v-slot="{ Component, route }" :key="$route.fullPath">
        <component :is="Component" :key="route.path" />
    </router-view>
    <FooterMain />
</template>

<script setup>
import { useRouter } from "vue-router";
const router = useRouter();

import HeaderMain from '../components/HeaderCommon.vue';
import FooterMain from '../components/FooterCommon.vue';
</script>

<style lang="scss">

</style>