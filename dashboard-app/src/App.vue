<template>
  <div class="flex">
    <Sidebar />

    <div class="flex-1">
      <Dashboard />
    </div>
  </div>
</template>

<script setup>
import Sidebar from "./components/Sidebar.vue";
import Dashboard from "./views/Dashboard.vue";
</script>
