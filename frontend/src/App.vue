<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="container">
  <header class="d-flex flex-wrap justify-content-center py-3 mb-4 border-bottom">
    <a href="/" class="d-flex align-items-center mb-3 mb-md-0 me-md-auto text-dark text-decoration-none">
      <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="40" height="32" />
    </a>

    <ul class="nav nav-pills">
      <li class="nav-item"><RouterLink to="/">Home</RouterLink></li>
      <li class="nav-item"><RouterLink to="/about">About</RouterLink></li>
    </ul>
  </header>
  </div>
  <RouterView />
</template>
