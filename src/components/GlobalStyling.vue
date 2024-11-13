

<template>
    <h1 class="text-red">Global Styling</h1>
    <p class="local">Tying local scope in this component</p>
</template>



<!-- global style -->

<!-- <style>
.text-red { 
  color: red;  
}
</style> -->


<!-- local style -->

<style scoped>
.text-red { 
  color: red;  
}
</style>