<script setup>
import { RouterLink, RouterView } from "vue-router";
import Header from "./components/Header.vue";
import Banner from "./components/Banner.vue";
import Categories from "./components/Categories.vue";
import Footer from "./components/Footer.vue";



</script>

<template>
  <section id="fullContainer">
    <Header />
    <Banner />
    <Categories />
    <Footer/>
  </section>
</template>


<style scoped>

</style>
