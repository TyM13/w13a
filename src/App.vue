<template>
  <div id="app">
    
    <header-content></header-content>
    <body-content></body-content>
    <footer-content></footer-content>
  </div>
</template>

<script>
import HeaderContent from "@/components/HeaderContent.vue";
import BodyContent from "@/components/BodyContent.vue";
import FooterContent from "@/components/FooterContent.vue";

export default {
  components: {
    HeaderContent,
    BodyContent,
    FooterContent,
  },
};
</script>

<style>
</style>
