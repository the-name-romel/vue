<script setup>
import {ref} from 'vue' 

const input = ref('Hi')
</script>
<template>
    <select v-model="input">
        <option value="web">web</option>
        <option value="design">design</option>
    </select>
    <p>p: {{ input }}</p>
</template>