<script setup>
import { RouterLink, RouterView } from 'vue-router'

import Magnify from 'vue-material-design-icons/Magnify.vue';
import Bell from 'vue-material-design-icons/Bell.vue';
</script>

<template>
  <div 
    id="TopNav"
    class="fixed right-0 flex items-center justify-between w-[calc(100%-240px)] h-[56px] border-b border-b-[#32323D]"
  >
    <div class="flex items-center w-full">
      <Magnify class="pl-6 mt-1 pr-2" fillColor="#7E7E88" :size="22" />
      <input 
        class="p-1 bg-transparent outline-none font-[300] placeholder-[#BEBEC7] text-[#FFFFFF] w-full max-w-xl"
        placeholder="Search"
        type="text"
      >
    </div>
    <div class="flex items-center pr-10">
      <div class="mr-4 p-1 hover:bg-gray-600 rounded-full cursor-pointer">
        <Bell fillColor="#FFFFFF" :size="20" />

      </div>
    </div>
  </div>

  <!-- <RouterView /> -->
</template>

<style scoped>

</style>
