<script setup>
 import HelloWorld from "./components/HelloWorld.vue";
 import Nstedcom from "./components/Parent.vue"

 const myChannel = "https://ravinyadav.vercel.app"
</script>

<template>
  <HelloWorld/>
  <Nstedcom/>
  <p>{{  }}</p>
  <a v-bind:href="myChannel">MY portfolio</a> <br>
  <a :href="myChannel">MY portfolio</a>

</template>

