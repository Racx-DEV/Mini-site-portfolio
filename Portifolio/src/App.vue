<template>
  <div class="min-h-screen flex flex-col justify-between bg-gray-50">
    <main class="flex-1">
      <NavBarComponents />
      <router-view />
      <FooterComponents/>
    </main>
  </div>
</template>

<script setup>
import NavBarComponents from './components/NavBarComponents.vue'
import FooterComponents from './components/FooterComponents.vue'
</script>
