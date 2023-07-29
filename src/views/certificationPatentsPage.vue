<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>
<template>
  <div class="about1">
    <!-- <h1>This is an about1 page</h1> -->
    <TheWelcome />
  </div>
</template>


<style>
@media (min-width: 1024px) {
  .about1 {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>