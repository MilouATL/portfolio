<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Introduction from "./components/Introduction.vue";

</script>

<template>
<div class="relative bg-white px-6 pt-10 pb-8 shadow-xl ring-1 ring-gray-900/5 sm:mx-auto sm:max-w-lg sm:rounded-lg sm:px-10">
  <img src="src/assets/milou-de-veen.jpeg" alt="">
      <Introduction class="text-3xl font-bold" name="Milou de Veen"/>
     <Introduction class="text-1l font-light" jobFunction="Front-end Developer"/>
</div>

</template>

<style>
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}
</style>
