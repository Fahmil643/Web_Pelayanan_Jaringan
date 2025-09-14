<template>
  <nav class="bg-gray-800 text-white p-5">
    <div class="container mx-auto flex items-center justify-between">
      <a href="#" class="text-xl font-bold">Logo</a>

      <div class="hidden md:flex space-x-4">
        <a
          href="#"
          class="relative mx-8 hover:text-gray-300 after:content-[''] after:absolute after:left-1/2 after:bottom-0 after:w-0 after:h-[2px] after:bg-gray-300 after:transition-all after:duration-500 after:ease-out hover:after:left-0 hover:after:w-full"
        >
          Home
        </a>
        <a
          href="#About"
          class="relative mx-8 hover:text-gray-300 after:content-[''] after:absolute after:left-1/2 after:bottom-0 after:w-0 after:h-[2px] after:bg-gray-300 after:transition-all after:duration-500 after:ease-out hover:after:left-0 hover:after:w-full"
        >
          Tentang Kami
        </a>
        <a
          href="#Layanan"
          class="relative mx-8 hover:text-gray-300 after:content-[''] after:absolute after:left-1/2 after:bottom-0 after:w-0 after:h-[2px] after:bg-gray-300 after:transition-all after:duration-500 after:ease-out hover:after:left-0 hover:after:w-full"
        >
          Layanan
        </a>
        
        <a
          href="#Kontak"
          class="relative mx-8 hover:text-gray-300 after:content-[''] after:absolute after:left-1/2 after:bottom-0 after:w-0 after:h-[2px] after:bg-gray-300 after:transition-all after:duration-500 after:ease-out hover:after:left-0 hover:after:w-full"
        >
          Kontak
        </a>
      </div>

      <div class="md:hidden">
        <button @click="isMobileMenuOpen = !isMobileMenuOpen" class="text-white focus:outline-none">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path :class="{ hidden: isMobileMenuOpen, block: !isMobileMenuOpen }" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
            <path :class="{ block: isMobileMenuOpen, hidden: !isMobileMenuOpen }" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
          </svg>
        </button>
      </div>
    </div>

    <div v-if="isMobileMenuOpen" class="md:hidden mt-4">
      <div class="flex flex-col space-y-2">
        <a href="#" class="block hover:bg-gray-700 px-4 py-2 rounded">Home</a>
        <a href="#" class="block hover:bg-gray-700 px-4 py-2 rounded">Tentang Kami</a>
        <a href="#" class="block hover:bg-gray-700 px-4 py-2 rounded">Layanan</a>
        <a href="#" class="block hover:bg-gray-700 px-4 py-2 rounded">Kontak</a>
      </div>
    </div>
  </nav>
</template>

<script setup>
import { ref } from "vue";

const isMobileMenuOpen = ref(false);
</script>
