<template>
  <div class="bg-white shadow rounded-xl p-5 flex items-center space-x-4 w-full">
    <div class="w-12 h-12 flex items-center justify-center rounded-lg" :class="iconBg">
      <span class="text-xl">{{ icon }}</span>
    </div>
    <div>
      <p class="text-3xl font-bold">{{ value }}</p>
      <p class="text-gray-500">{{ label }}</p>
    </div>
  </div>
</template>

<script setup>
defineProps({
  icon: String,
  iconBg: String,
  value: Number,
  label: String,
})
</script>
