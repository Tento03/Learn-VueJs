<template>
  <div class="bg-purple-50 min-h-screen">

    <HeaderBar />

    <div class="p-6">

      <!-- Greeting -->
      <h2 class="text-3xl font-bold">Selamat Datang 👋</h2>
      <p class="text-gray-500 mb-6">Ringkasan aktivitas dokumen Anda</p>

      <!-- Statistik -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-5 mb-10">
        <StatCard icon="✔" iconBg="bg-green-100" :value="10" label="Disetujui" />
        <StatCard icon="✖" iconBg="bg-red-100" :value="5" label="Ditolak" />
        <StatCard icon="⏳" iconBg="bg-yellow-100" :value="2" label="Ditunda" />
      </div>

      <!-- Akses Cepat -->
      <h3 class="text-lg font-semibold mb-3">Akses Cepat</h3>
      <div class="grid grid-cols-4 gap-4 text-center mb-10">
        <QuickActionCard icon="📤" label="Upload" />
        <QuickActionCard icon="📁" label="Dokumen" />
        <QuickActionCard icon="⚙️" label="Status" />
        <QuickActionCard icon="🔍" label="Cari" />
      </div>

      <!-- Dokumen Terbaru -->
      <h3 class="text-lg font-semibold mb-3">Dokumen Terbaru</h3>

      <div class="space-y-3">
        <div class="bg-white shadow p-3 rounded-lg flex justify-between">
          <span>Surat Keterangan Aktif</span>
          <span class="text-green-600">Disetujui</span>
        </div>

        <div class="bg-white shadow p-3 rounded-lg flex justify-between">
          <span>Surat Permohonan Dana</span>
          <span class="text-red-600">Ditolak</span>
        </div>
      </div>

    </div>
  </div>
</template>

<script setup>
import HeaderBar from "../components/HeaderBar.vue";
import StatCard from "../components/StatCard.vue";
import QuickActionCard from "../components/QuickActionCard.vue";
</script>
