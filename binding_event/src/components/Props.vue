<template>
    <input v-model="name" placeholder="name" size="20"></input>
    <button @click="count++">Increase</button>
    <p>name: {{ name }}</p>
    <p>name: {{ count }}</p>
    <p v-if="isLoggedIn">Welcome</p>
    <p v-else>Login</p>
    <ul>
        <li v-for="fruit in fruits" :key="fruit">{{ fruit }}</li>
    </ul>
</template>

<script setup>
import {ref} from 'vue';

const name=ref("");
const count=ref(0);
const isLoggedIn=ref(true);
const fruits=ref(["as","a","s"]);
</script>