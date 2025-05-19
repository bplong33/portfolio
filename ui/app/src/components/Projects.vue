<script lang="ts">
import { reactive } from 'vue';
import ProjectCard from '../components/ProjectCard.vue'

let projects = reactive([
  { name: "proj1", description: "This is the first project" },
  { name: "proj2", description: "This is the second project" },
  { name: "proj3", description: "This is the third project" },
])
</script>

<template>
  <div>
    <h1 class="text-2xl text-center">Projects</h1>
  </div>
  <div class="flex flex-row flex-wrap">
    <li v-for="proj in projects" :key="name">
      <ProjectCard :name="proj.name" :description="proj.description" />
    </li>
  </div>
</template>
