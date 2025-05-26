<template>
  <div class="flex flex-col items-center bg-[#080c1c] rounded-xl p-4 shadow hover:scale-105 hover:bg-white transition cursor-default w-24">
    <img
      v-if="icon"
      :src="getIconPath(icon)"
      :alt="label"
      class="w-8 h-8 mb-2"
      loading="lazy"
    />
    <span class="font-medium text-sm text-center text-[#4facfe] transition-colors">{{ label }}</span>
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

