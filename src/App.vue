<script setup>
import Navbar from './components/NavbarComponent.vue'
import Footer from './components/FooterComponent.vue'
</script>


<template>
  <div class=" bg-[url(https://news.epopculture.com/wp-content/uploads/2025/02/capa-pokemon.jpg)] bg-cover flex flex-col min-h-screen bg-gray-100">
    <Navbar />
    <div class="main container mx-auto px-4 py-6">
      <router-view></router-view>
    </div>
    <Footer />
  </div>
</template>