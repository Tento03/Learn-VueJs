<template>
  <div class="flex flex-col items-center cursor-pointer">
    <div class="w-16 h-16 rounded-xl bg-indigo-100 flex items-center justify-center text-3xl">
      {{ icon }}
    </div>
    <p class="mt-2 text-sm">{{ label }}</p>
  </div>
</template>

<script setup>
defineProps({
  icon: String,
  label: String,
})
</script>
