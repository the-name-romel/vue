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

    <!-- Conditional--> 
    <p v-if="input == 'web'"> Web Development</p>
    <p v-else="input == 'design'"> Designing</p>
</template>