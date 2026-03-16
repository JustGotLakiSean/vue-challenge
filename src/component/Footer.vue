<script setup>
import {ref} from 'vue'
const footer = ref("All Rights Reserved")
</script>

<template>
    <footer>
        <span>{{ footer }} &copy; 2026</span>
    </footer>
</template>

<style scoped>
footer {
    position: fixed;
    margin: 0 auto;
    bottom: 0;
    text-align: center;
    color: #CCD6D9;
    padding-bottom: 20px;
}

footer span {
    font-family: cursive;
}
</style>