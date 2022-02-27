<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Footer from './components/Footer.vue'
import Header from './components/Header.vue'
</script>

<template>
  <div class="min-h-screen w-full">
    <Header></Header>
    <div class="flex justify-center">
      <router-view></router-view>
    </div>
    <Footer></Footer>
  </div>
</template>

<style>
</style>
