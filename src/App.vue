<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Main from './components/Main.vue'
import Header from './components/Header.vue'
import Features from "./components/Features.vue";
</script>

<template>
  <div class="relative overflow-x-clip">
    <Header/>
    <Main/>
    <Features/>
  </div>

</template>

<style>
@import url('https://css.gg/css');
@tailwind base;
@tailwind components;
@tailwind utilities;
</style>
