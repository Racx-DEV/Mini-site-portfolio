<template>
  <section class="min-h-screen w-full flex flex-col justify-center items-center bg-[#0a1931] text-white px-4 py-10">
    <h1 class="w-full text-5xl md:text-6xl font-extrabold text-blue-200 mb-8 drop-shadow-lg text-center">
      Sobre Mim
    </h1>
    
    <!-- FORMAÇÃO -->
    <div class="w-full flex flex-col items-center mb-10">
      <h2 class="text-2xl font-semibold text-blue-300 mb-4">Formação</h2>
      <p class="text-blue-100 mb-2 text-lg text-center">
        Graduação em Análise e Desenvolvimento de Sistemas<br>
        <span class="text-sm text-blue-300">Previsão de conclusão: 2026</span>
      </p>
    </div>

    <!-- TRAJETÓRIA -->
    <div class="w-full flex flex-col items-center mb-10">
      <h2 class="text-2xl font-semibold text-blue-300 mb-4">Minha Trajetória</h2>
      <p class="text-blue-50 text-justify text-lg max-w-4xl">
        Sempre fui movido pela curiosidade e pelo desejo de aprender coisas novas.<br>
        Estou em constante evolução, buscando aprimorar minhas habilidades técnicas e contribuir para projetos desafiadores e inovadores.
      </p>
    </div>

    <!-- HABILIDADES -->
    <div class="w-full flex flex-col items-center">
      <h2 class="text-2xl font-semibold text-blue-300 mb-6">Habilidades Técnicas</h2>

      <!-- FRONT-END -->
      <div class="mb-8 w-full">
        <p class="text-blue-200 text-xl font-bold mb-4">Front-end</p>
        <div class="flex flex-wrap gap-6">
          <SkillCard icon="html-5.svg" label="HTML" />
          <SkillCard icon="icons8-css.svg" label="CSS" />
          <SkillCard icon="icons8-tailwind-css.svg" label="Tailwind" />
          <SkillCard icon="icons8-bootstrap.svg" label="Bootstrap" />
          <SkillCard icon="icons8-javascript.svg" label="JavaScript" />
          <SkillCard icon="icons8-visualizar-js.svg" label="Vue.js" />
        </div>
      </div>

      <!-- BACK-END -->
      <div class="mb-8 w-full">
        <p class="text-blue-200 text-xl font-bold mb-4">Back-end</p>
        <div class="flex flex-wrap gap-6">
          <SkillCard icon="python.svg" label="Python" />
          <SkillCard icon="php.svg" label="PHP" />
          <SkillCard icon="csharp.svg" label="C#" />
        </div>
      </div>

      <!-- BANCO DE DADOS -->
      <div class="mb-8 w-full">
        <p class="text-blue-200 text-xl font-bold mb-4">Banco de Dados</p>
        <div class="flex flex-wrap gap-6">
          <SkillCard icon="sql.svg" label="SQL" />
          <SkillCard icon="mysql.svg" label="MySQL" />
        </div>
      </div>

      <!-- DEVOPS -->
      <div class="mb-8 w-full">
        <p class="text-blue-200 text-xl font-bold mb-4">DevOps</p>
        <div class="flex flex-wrap gap-6">
          <SkillCard icon="docker.svg" label="Docker" />
          <SkillCard icon="docker-compose.svg" label="Docker Compose" />
        </div>
      </div>

      <!-- VERSIONAMENTO -->
      <div class="mb-8 w-full">
        <p class="text-blue-200 text-xl font-bold mb-4">Versionamento</p>
        <div class="flex flex-wrap gap-6">
          <SkillCard icon="git.svg" label="Git" />
          <SkillCard icon="github.svg" label="GitHub" />
        </div>
      </div>

      <!-- INFRAESTRUTURA -->
      <div class="mb-8 w-full">
        <p class="text-blue-200 text-xl font-bold mb-4">Infraestrutura</p>
        <div class="flex flex-wrap gap-6">
          <SkillCard icon="linux.svg" label="Linux" />
          <SkillCard icon="windows.svg" label="Windows" />
        </div>
      </div>

      <!-- DADOS / ANÁLISE -->
      <div class="mb-8 w-full">
        <p class="text-blue-200 text-xl font-bold mb-4">Dados / Análise</p>
        <div class="flex flex-wrap gap-6">
          <SkillCard icon="excel.svg" label="Excel" />
          <SkillCard icon="power-bi.svg" label="Power BI" />
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import SkillCard from '../components/SkillCardComponent.vue'
</script>
