<template>
  <div class="w-64 bg-gray-900 text-white h-screen p-5 flex flex-col">
    
    <!-- Judul Sidebar -->
    <div class="text-2xl font-bold mb-10">
      Dashboard
    </div>

    <!-- Menu -->
    <nav class="flex flex-col gap-3">

      <!-- Home -->
      <button class="flex items-center gap-3 hover:bg-gray-700 p-2 rounded">
        <span class="material-icons">home</span>
        <span>Home</span>
      </button>

      <!-- Surat Masuk -->
      <button class="flex items-center gap-3 hover:bg-gray-700 p-2 rounded">
        <span class="material-icons">inbox</span>
        <span>Surat Masuk</span>
      </button>

      <!-- Surat Keluar -->
      <button class="flex items-center gap-3 hover:bg-gray-700 p-2 rounded">
        <span class="material-icons">outbox</span>
        <span>Surat Keluar</span>
      </button>

      <!-- Pengaturan -->
      <button class="flex items-center gap-3 hover:bg-gray-700 p-2 rounded">
        <span class="material-icons">settings</span>
        <span>Pengaturan</span>
      </button>

    </nav>
  </div>
</template>

<script setup></script>

<style>
@import url('https://fonts.googleapis.com/icon?family=Material+Icons');
</style>
