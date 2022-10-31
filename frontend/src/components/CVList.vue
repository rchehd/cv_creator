<template>
  <ul id="articles">
    <li v-for="article in articles" :key="article.id">
      <CVItem :article="article"></CVItem>
    </li>
  </ul>
</template>

<script>
import axios from 'axios';
import CVItem from "./cv/CVItem";

export default {
  components: {CVItem},
  data() {
    return {
      articles: null
    }
  },
  mounted() {
    const res = axios.get('http://drupal.docker.localhost/api/recipes');
    res.then(res => (this.articles = res.data.data));
  },
}
</script>