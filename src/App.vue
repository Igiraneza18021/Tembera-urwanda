<script setup>
import NavBar from './components/NavBar.vue'
import Footer from './components/footer.vue';
</script>

<template>
  <div class="min-h-screen flex flex-col bg-white">
    <NavBar />
    <div class="flex-grow">
      <!-- Content is rendered by NavBar's RouterView -->
    </div>
    <Footer />
  </div>
</template>
