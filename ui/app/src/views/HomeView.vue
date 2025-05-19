<script setup lang="ts">
import Projects from '../components/Projects.vue'
// import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <!-- Todo: set min-height -->
    <container class="flex flex-col w-full h-[35rem] bg-slate-800 items-center
      justify-center space-y-6 rounded-2xl mb-10">
      <div class="w-[40rem] space-y-3">
        <h1 class="text-orange-600 text-5xl">Brandon Long</h1>
        <h3 class="text-xl mb-8 ml-1">Software Developer</h3>
        <div class="flex flex-row ">
          <!-- <div class="bg-orange-800 mr-3 w-2 h-full rounded-full"></div> -->
          <p class="pl-1">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fugit, voluptatum? Vitae commodi,
            minima ab
            praesentium eaque corporis sint! Corporis illum reiciendis ipsam veritatis, aut animi nisi. Cum in alias
            doloribus!</p>
        </div>
      </div>
    </container>
    <!-- <TheWelcome /> -->
    <Projects />
  </main>
</template>
