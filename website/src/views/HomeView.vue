<script setup lang="ts">

import { useRoute } from 'vue-router'

const route = useRoute();

document.title = `André Felipe | ${String(route.name)}`;
</script>


<template>

    <!-- <TheWelcome /> -->
     <h1>Home <i class="bi bi-body-text"></i></h1>

    
      
      
</template>


<style scoped>
/* Add your CSS styles here */
</style>
