<template>
  <div class="container">
    <Header />
    <Hero />
    <AboutBrand />
    <Product />
  </div>
</template>

<script setup>
import Header from "./components/Layout/Header.vue";
import Hero from "./components/Hero.vue";
import AboutBrand from "./components/AboutBrand.vue";
import Product from "./components/Products4Column.vue";
</script>

<style lang="scss">
@import "./assets/styles/global.scss";
</style>
