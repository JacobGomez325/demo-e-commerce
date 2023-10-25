<template>
 <div>
  <TheNavbar />
  <TheHeader />
  <main class="container mx-auto mt-6 mb-3 p-5">
    <TabsMenu />
    <div class="my-4 grid grid-cols-3 gap-5">
      <CardCart />
      <CardCart />
      <CardCart />
      <CardCart />
      <CardCart />
    </div>
  </main>
  <TheFooter />
 </div>
</template>
<script setup>
import TheNavbar from '@/components/TheNavbar.vue'
import TheHeader from '@/components/TheHeader.vue'
import TheFooter from '@/components/TheFooter.vue'
import TabsMenu from '@/components/TabsMenu.vue'
import CardCart from '@/components/CardCart.vue'
</script>
