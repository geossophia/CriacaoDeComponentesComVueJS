<script>
import ArticleBlock from "@/components/ArticleBlock.vue";
export default {
  name: "PrincipalContent",
  components: {
    ArticleBlock,
  },
};
</script>
<template>
  <main id="content">
    <ArticleBlock class="BlocoS" />
    <ArticleBlock />
    <ArticleBlock class="BlocoM" />
    <ArticleBlock class="BlocoM" />
    <ArticleBlock />
    <ArticleBlock class="BlocoS" />
  </main>
</template>
<style></style>
