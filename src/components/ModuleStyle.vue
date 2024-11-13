


<template>
    <h1 v-bind:class="$style['m-class']">This is module style here</h1>
    <!-- or -->
    <h1 :class="$style.anotherClass">This is module style here camel case</h1>
    <h1 :class="customizename.anotherClass">This is module style here camel case</h1>

</template>




<style module>
   /* kabab case */

   .m-class {
    background-color: red;
    color: white;
   }


   /* camel case */
   /* .anotherClass {
    background: blue;
    color: white;
   } */
</style>

<style module="customizename">
   /* kabab case */

   .m-class {
    background-color: red;
    color: white;
   }


   /* camel case */
   .anotherClass {
    background: blue;
    color: white;
   }
</style>