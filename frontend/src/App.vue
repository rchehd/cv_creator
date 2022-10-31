<script setup>
import { RouterView } from 'vue-router'
import Header from './components/Header'
import Footer from './components/Footer'
</script>

<template>
  <div class="container">
    <Header></Header>
    <RouterView />
    <Footer></Footer>
  </div>

</template>
