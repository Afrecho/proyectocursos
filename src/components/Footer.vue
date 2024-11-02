<template>
<footer>
    <p> &copy; {{ currentYear }} Mi sitio web</p>


</footer>

</template>

<script setup>

import { ref } from 'vue';

const currentYear = ref(new Date().getFullYear());

console.log(currentYear.value);

const elDatazo = 'ahora no se';

console.log(elDatazo);

</script>

<style scoped>

    footer{
        background-color: rgb(107, 88, 124);
        color: bisque;
        min-width: 100vw;
        height: 30px;
        padding: 10px;
        text-align: center;
    }

</style>