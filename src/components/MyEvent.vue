

<script setup>
import {ref} from "vue"
let count = ref(0);


const incrementCounter = () => {
    count.value++ //value comming from ref
}

const decrementCounter = () => {
    count.value-- 
}
</script>


<template>
    <h1>count: {{ count }}</h1>

    <!-- <button v-on:click="count++">increase</button>
    <button @:click="count++">increase</button> -->
    <button @:click="incrementCounter">increase</button>
    <button @:click="decrementCounter">increase</button>

</template>