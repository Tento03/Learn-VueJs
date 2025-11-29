<template>
    <button @click="plus++">Tambah</button><br><br>
    <button @click="minus--">Kurang</button><br>
    <p>Total Sum : {{ plus }}</p>
    <p>Total Minus : {{ minus }}</p>
</template>

<script setup>
import {ref} from "vue";

const plus=ref(0);
const minus=ref(0);
</script>