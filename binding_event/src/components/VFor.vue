<template>
    <ul>
        <li v-for="fruit in fruits" :key="fruit">{{ fruit }}</li>
    </ul>
</template>

<script setup>
import {ref} from "vue";

const fruits=ref(['apel','mangga','jeruk']);
</script>