<script>
import { RouterLink, RouterView } from 'vue-router'
import Topheader from '@/components/Topheader.vue';
import Footer from '@/components/Footer.vue';
</script>

<template>
  <div class="navbar">
    <Topheader />
  </div>
  <RouterView />
  <div class="footer">
    <Footer/>
  </div>
</template>