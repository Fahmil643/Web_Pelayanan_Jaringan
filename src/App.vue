<template>
  <div id="app" class="flex flex-col min-h-screen">
    <Navbar />

   <Componen />

    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Componen from './components/Componen.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Componen,
    Footer
  }
};
</script>

<style>
/* Tambahkan styling global atau Tailwind di sini */
</style>