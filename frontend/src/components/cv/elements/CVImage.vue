<template>
<!--  <p>{{ src }}</p>-->
<!--  <p>{{ getImage(src) }}</p>-->
<!--  <img :src="test">-->
</template>

<script>
import axios from "axios";

export default {
  props: ['src'],
  data() {
    return {
      image: null
    }
  },
  mounted() {

  },
  // methods: {
  //   getImage(src) {
  //     const res = axios.get(src);
  //     console.log(res);
  //     return res;
  //   }
  // }
}
</script>