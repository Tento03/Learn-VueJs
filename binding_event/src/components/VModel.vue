<template>
    <input v-model="name" placeholder="input nama" size="20"></input><br>
    <input v-model="hoby" placeholder="input hoby" size="20"></input><br>
    <p>Name: {{ name }}</p>
    <p>Hobby: {{ hoby }}</p>
</template>

<script setup>
import {ref} from "vue";

const name=ref("");
const hoby=ref("");
</script>