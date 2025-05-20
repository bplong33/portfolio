<script setup lang="ts">
const props = defineProps<{
  name: string
  description: string
}>()
</script>

<template>
  <div class="h-80 w-64 border-amber-500 rounded-md border-2 p-3">
    <h2>{{ props.name }}</h2>
    <p>{{ props.description }}</p>
  </div>
</template>
