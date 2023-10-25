<template>
  <div class="bg-gray-900 p-5 text-white">
    <p>Tout les droits réservés &copy; {{ year }} </p>
  </div>
</template>

<script setup>
import {computed} from 'vue'
const year = computed(()=> {
  const date = new Date()
  return date.getFullYear()
  
})
</script>

<style scoped>

</style>