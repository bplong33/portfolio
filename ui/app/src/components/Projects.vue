<script setup lang="ts">
import { reactive } from 'vue';
import ProjectCard from '@/components/ProjectCard.vue'

let projects = reactive([
  { name: "proj1", description: "This is the first project" },
  { name: "proj2", description: "This is the second project" },
  { name: "proj3", description: "This is the third project" },
])
</script>

<template>
  <div class="mb-6">
    <h1 class="text-2xl text-center">Projects</h1>
  </div>
  <div class="flex flex-row flex-wrap justify-center space-around space-x-8">
    <div v-for="proj in projects" :key="proj.name">
      <ProjectCard :name="proj.name" :description="proj.description" />
    </div>
  </div>
</template>
