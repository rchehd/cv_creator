<template>
  <ul id="ingredients">
    <li v-for="ingredient in ingredients">
      <p>{{ ingredient }}</p>
    </li>
  </ul>
</template>

<script>
export default {
  props: ['ingredients'],
}
</script>