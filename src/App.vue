<script setup>
import { RouterLink, RouterView } from 'vue-router'
import TopNavBar from '@/components/TopNavBar.vue'
</script>

<template>
  <div class="navbar">
    <TopNavBar/>
  </div>
  <RouterView />
</template>