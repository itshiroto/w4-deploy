<script setup>
const config = useRuntimeConfig()

let name = config.public.STUDENT_NAME ?? "Agus"
let nim = config.public.STUDENT_NIM ?? "00000012345"
</script>

<template>
  <div class="min-h-screen w-full flex flex-col gap-4 items-center justify-center bg-gray-900 text-white">
    <h1 class="font-bold text-6xl">Hello World!</h1>
    <p class="text-2xl">{{ name }} - {{ nim }}</p>
  </div>
</template>
