<template>
    <p v-if="isLoggedIn">Welcome</p>
    <p v-else>Silahkan Login</p>
</template>

<script setup>
import {ref} from "vue";

const isLoggedIn=ref(false);
</script>