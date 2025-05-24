<template>
  <div class="flex flex-col items-center bg-white/10 rounded-xl p-4 shadow hover:scale-105 transition cursor-default w-24">
    <span v-html="iconSvg"></span>
    <span class="mt-2 font-medium text-sm text-blue-100 text-center">{{ label }}</span>
  </div>
</template>

<script setup>
import { computed } from 'vue'

const props = defineProps({
  icon: String,
  label: String
})

const icons = {
  html: ``,
  css: ``,
  tailwind: ``,
  bootstrap: ``,
  js: ``,
  vue: ``,
  php: ``,
  csharp: ``,
  sql: ``,
  mysql: ``,
  docker: ``,
  "docker-compose": ``,
  git: ``,
  github: ``,
  linux: ``,
  windows: ``,
  excel: ``,
  powerbi: ``,
}

const iconSvg = computed(() => icons[props.icon] || '')
</script>
