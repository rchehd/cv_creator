<template>
<!--  <CVImage :src="article.relationships.image.links.self.href" />-->
<!--  {{ article.attributes.internalId }}-->
  <CVTitle :text="article.attributes.title" />
  <CVIngredients :ingredients="article.attributes.ingredients"/>
  <CVDescription :text="article.attributes.instructions" />
</template>

<script>
import CVImage from "./elements/CVImage";
import CVTitle from "./elements/CVTitle";
import CVIngredients from "./elements/CVIngrediets"
import CVDescription from "./elements/CVDescription"

export default {
  components: {
    CVImage,
    CVTitle,
    CVIngredients,
    CVDescription,
  },
  props: ['article'],
}
</script>