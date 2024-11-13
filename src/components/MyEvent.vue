

<script setup>
import {ref} from "vue"
let count = ref(0);
</script>


<template>
    <h1>count: {{ count }}</h1>

    <button v-on:click="count++">increase</button>
    <button @:click="count++">increase</button>

</template>