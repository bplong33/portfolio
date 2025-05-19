<script lang="ts">
defineProps<{
  name: string
  description: string
}>()
</script>

<template>
  <div class="h-80 w-36"">
    <h2>{{ name }}</h2>
    <p>{{ description }}</p>
  </div>
</template>
