<script setup>
import Logo from './assets/logo.svg?raw'
</script>
<template>
  <div class="flex h-screen w-screen items-center justify-center bg-gray-900">
    <div class="min-h-[300px] min-w-[500px] rounded bg-white p-5 text-center">
      <div class="flex h-[300px] w-full flex-col items-center justify-center">
        <div v-html="Logo" class="mx-auto h-32 w-32" />

        <div class="text-2xl">Sidekick-coder template</div>
      </div>
    </div>
  </div>
</template>
