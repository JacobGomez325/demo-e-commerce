<template>
  <div class="px-4 py-5 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8">
    <div class="relative flex items-center justify-between">
      <router-link to=""  aria-label="home" title="shopstart" class="inline-flex items-center">
        <LogoIcon width="2.2em" height="2.2em" />
        <span class="ml-2 text-xl font-bold tracking-wide text-gray-800 ">ShopStart</span>
      </router-link>
      <ul class="flex items-center space-x-8 lg:flex">
        <li>
          <router-link to=""  aria-label="acceuil" title="acceuil"
            class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400">Acceuil</router-link>
        </li>
        <li>
          <router-link to=""  aria-label="produits" title="produits"
            class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400">Produits</router-link>
        </li>
        <li>
          <router-link to=""  aria-label="contactez-nous" title="contactez-nous"
            class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400">Contactez-nous</router-link>
        </li>
        
      </ul>
      <div class="relative ">
        <span class="absolute bg-red-500 text-white rounded-full px-1 text-xs right-0 -top-1">2</span>
        <BagIcon  width="2.2em" height="2.2em" />
      </div>
     
    </div>
  </div>
</template>

<script setup>
import LogoIcon from '@/components/icons/LogoIcon.vue'
import BagIcon from '@/components/icons/BagIcon.vue'

</script>