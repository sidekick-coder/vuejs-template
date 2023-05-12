<script setup>
import Logo from './assets/logo.svg?raw'
</script>
<template>
  <div class="h-screen w-screen flex items-center justify-center bg-gray-900 text-white" >
    <div class="text-center">
      <div v-html="Logo" class="w-32 h-32 mx-auto" />

      <div class="text-xl">
        Sidekick-coder template
      </div>

    </div>
  </div>
</template>