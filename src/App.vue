<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Header from "./components/Header.vue"
import Footer from "./components/Footer.vue"
</script>

<template>

  <Header></Header>

  <RouterView />

  <Footer/>

</template>

<style scoped>

</style>
