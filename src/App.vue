<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import TopNavBar from '@/components/TopNavBar.vue'
import Footer from '@/components/Footer.vue';
import TopNavBar from '@/components/TopNavBar.vue';
</script>

<template>
  <div class="navbar">
    <TopNavBar/>
  </div>
  <RouterView />
  <div class="footer">
    <Footer/>
  </div>
</template>