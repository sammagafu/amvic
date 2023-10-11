<script>
import { RouterLink, RouterView } from 'vue-router';
import Footer from '@/components/Footer.vue';
import Topheader from './components/Topheader.vue';

export default {
  components: {
    Topheader,Footer // Register your custom component here
  },
  // Other Vue App configuration
};
</script>


<template>
  <div class="navbar">
    <Topheader/>
  </div>
  <RouterView />
  <div class="footer">
    <Footer />
  </div>
</template>


