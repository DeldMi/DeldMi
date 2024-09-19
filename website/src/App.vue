<script setup lang="ts">
import { RouterView } from 'vue-router'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <header>
    <Header />
  </header>

  <main>
    <RouterView />
  </main>

  <footer class="">
    <Footer />
  </footer>
  
</template>

<style scoped>


/* @media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    align-items: center;
    justify-content: space-between;
    

  }
}
*/
</style>
