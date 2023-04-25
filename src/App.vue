<script setup>
import {RouterView } from 'vue-router'
import Navigation from './components/Navigation.vue';
</script>

<template>
  <div class="font-Roboto flex flex-col min-h-screen bg-weather-primary">
    <navigation/>
    <RouterView />
  </div>
  
</template>

<style scoped>

</style>
