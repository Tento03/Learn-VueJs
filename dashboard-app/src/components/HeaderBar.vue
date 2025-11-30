<template>
  <header class="w-full h-16 flex items-center justify-between px-5 
    bg-gradient-to-r from-indigo-400 to-purple-500 text-white shadow">

    <div class="flex items-center space-x-3">
      <button class="text-2xl" @click="$emit('toggleSidebar')">&#9776;</button>
      <h1 class="text-xl font-bold">Dashboard</h1>
    </div>

    <div class="flex items-center space-x-3">
      <div class="relative">
        <input
          type="text"
          placeholder="Cari surat..."
          class="bg-white/20 placeholder-white/80 text-white px-4 py-2 rounded-full pl-10 w-64"
        >
        <span class="absolute left-3 top-2.5 text-white text-lg">🔍</span>
      </div>

      <div class="w-10 h-10 rounded-full bg-white border-2 border-red-400 flex items-center justify-center">
        <span class="text-xs text-red-500 font-bold">User</span>
      </div>
    </div>

  </header>
</template>
