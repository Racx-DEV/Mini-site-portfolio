<template>
  <nav class="bg-[#071427] text-white py-3 px-8 flex justify-between items-center shadow-md">
    <router-link to="/" class="text-lg font-bold hover:text-blue-400 transition">Portfólio</router-link>
    <ul class="flex space-x-8">
      <li>
        <router-link to="/" class="hover:text-blue-400 transition">Home</router-link>
      </li>
      <li>
        <router-link to="/about" class="hover:text-blue-400 transition">Sobre</router-link>
      </li>
      <li>
        <router-link to="/contact" class="hover:text-blue-400 transition">Contato</router-link>
      </li>
    </ul>
  </nav>
</template>
