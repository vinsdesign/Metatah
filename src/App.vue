<script setup>
import { RouterLink, RouterView } from 'vue-router'
import FirstPage from './views/FirstPage.vue'
import SecondPage from './views/SecondPage.vue'
</script>

<template>
  <RouterLink :to="{ name: 'SecondPage' }"><SecondPage /></RouterLink>
</template>

<style scoped></style>
