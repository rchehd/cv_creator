<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <header class="d-flex flex-wrap justify-content-center py-3 mb-4 border-bottom">
    <a href="/" class="d-flex align-items-center mb-3 mb-md-0 me-md-auto text-dark text-decoration-none">
      <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="40" height="32" />
    </a>
    <ul class="nav nav-pills">
      <li class="nav-item"><RouterLink to="/"><a href="#" class="nav-link" aria-current="page">Home</a></RouterLink></li>
      <li class="nav-item"><RouterLink to="/about"><a href="#" class="nav-link">About</a></RouterLink></li>
    </ul>
  </header>
</template>