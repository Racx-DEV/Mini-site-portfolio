<template>
  <section class="min-h-screen flex flex-col justify-center items-center bg-[#0a1931] text-white">
    <h1 class="text-5xl font-extrabold text-blue-200 mb-4 drop-shadow-lg text-center">
      Seja bem-vindo!
    </h1>
    <p class="text-xl text-blue-100 mb-6 text-center max-w-2xl">
      Sou Raul, estudante de Análise e Desenvolvimento de Sistemas.<br>
      Este portfólio foi criado com Vue 3, Vite e Tailwind CSS.
    </p>

    <div class="flex gap-4">
      <router-link
        to="/about"
        class="bg-blue-700 hover:bg-blue-900 transition px-6 py-3 rounded-2xl font-bold shadow-md text-lg"
      >
        Sobre mim
      </router-link>
      <router-link
        to="/contact"
        class="bg-transparent border border-blue-500 hover:bg-blue-900 transition px-6 py-3 rounded-2xl font-bold shadow-md text-lg"
      >
        Contato
      </router-link>
    </div>
  </section>
</template>

<script setup>
// Por enquanto, nenhum JS necessário aqui
</script>
