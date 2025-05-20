<script setup lang="ts">
import Intro from '@/components/Intro.vue';
import Projects from '@/components/Projects.vue'
</script>

<template>
  <main>
    <!-- TODO: set min-height -->
    <div class="flex flex-col h-[35rem] bg-slate-800 items-center
      justify-center space-y-6 mb-10">
      <Intro />
    </div>
    <div>
      <Projects />
    </div>
  </main>
</template>
