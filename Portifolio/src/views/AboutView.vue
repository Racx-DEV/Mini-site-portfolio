<template>
  <section class="min-h-screen w-full flex flex-col justify-center items-center bg-[#0a1931] text-white px-4 py-10">
    <h1 class="w-full text-5xl md:text-6xl font-extrabold text-blue-200 mb-8 drop-shadow-lg text-center">Sobre Mim</h1>
    
    <!-- HABILIDADES -->
    <div class="w-full flex flex-col items-center">
      <h2 class="text-2xl font-semibold text-blue-300 mb-6">Habilidades Técnicas</h2>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-6 mb-12">
        <!-- FRONT-END -->
        <SkillCard icon="html" label="HTML" />
        <SkillCard icon="css" label="CSS" />
        <SkillCard icon="tailwind" label="Tailwind" />
        <SkillCard icon="bootstrap" label="Bootstrap" />
        <SkillCard icon="js" label="JavaScript" />
        <SkillCard icon="vue" label="Vue.js" />
        

        <!-- BACK-END -->
        <SkillCard icon="python" label="Python" />
        <SkillCard icon="php" label="PHP" />
        <SkillCard icon="csharp" label="C#" />

        <!-- DATABASE -->
        <SkillCard icon="sql" label="SQL" />
        <SkillCard icon="mysql" label="MySQL" />

        <!-- DEVOPS -->
        <SkillCard icon="docker" label="Docker" />
        <SkillCard icon="docker-compose" label="Docker Compose" />

        <!-- VERSIONAMENTO -->
        <SkillCard icon="git" label="Git" />
        <SkillCard icon="github" label="GitHub" />

        <!-- INFRA -->
        <SkillCard icon="linux" label="Linux" />
        <SkillCard icon="windows" label="Windows" />

        <!-- DADOS/ANÁLISE -->
        <SkillCard icon="excel" label="Excel" />
        <SkillCard icon="powerbi" label="Power BI" />
      </div>
    </div>

    <!-- FORMAÇÃO -->
    <div class="w-full flex flex-col items-center mb-10">
      <h2 class="text-2xl font-semibold text-blue-300 mb-4">Formação</h2>
      <p class="text-blue-100 mb-2 text-lg text-center">
        Graduação em Análise e Desenvolvimento de Sistemas<br>
        <span class="text-sm text-blue-300">Previsão de conclusão: 2026</span>
      </p>
    </div>
    <!-- TRAJETÓRIA -->
    <div class="w-full flex flex-col items-center">
      <h2 class="text-2xl font-semibold text-blue-300 mb-4">Minha Trajetória</h2>
      <p class="text-blue-50 text-justify text-lg max-w-4xl">
        Sempre fui movido pela curiosidade e pelo desejo de aprender coisas novas.<br>
        Estou em constante evolução, buscando aprimorar minhas habilidades técnicas e contribuir para projetos desafiadores e inovadores.
      </p>
    </div>
  </section>
</template>

<script setup>
import SkillCard from '../components/SkillCardComponent.vue'
</script>
