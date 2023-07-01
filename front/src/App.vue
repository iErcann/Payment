<script setup>
import { RouterLink, RouterView } from "vue-router";
import NavBar from "./components/NavBar.vue";
import Product from "./components/Product.vue";
</script>

<template>
  <header>
    <NavBar />
  </header>
  <div class="container mx-auto mt-8">
    <RouterView />
  </div>
</template>
