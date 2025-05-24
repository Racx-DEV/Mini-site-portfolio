<template>
  <div class="flex flex-col items-center bg-white/10 rounded-xl p-4 shadow hover:scale-105 transition cursor-default w-24">
    <img
      v-if="icon"
      :src="getIconPath(icon)"
      :alt="label"
      class="w-8 h-8 mb-2"
      loading="lazy"
    />
    <span class="font-medium text-sm text-blue-100 text-center">{{ label }}</span>
  </div>
</template>

<script setup>
const props = defineProps({
  icon: String,
  label: String
})

// Função para montar o caminho do SVG na pasta assets/icons
const getIconPath = (icon) => {
  // Se estiver em src/assets/icons/
  return new URL(`../assets/icons/${icon}`, import.meta.url).href
}
</script>
