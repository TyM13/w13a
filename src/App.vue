<template>
  <div id="app">
    <header-content></header-content>
    <body-content></body-content>
    <footer-content></footer-content>
  </div>
</template>

<script>                              // ^(wont let me comment in most places) puts the content on the page that was in the corresponding components^
import HeaderContent from "@/components/HeaderContent.vue"; // import HeaderContent from the HeaderContent component
import BodyContent from "@/components/BodyContent.vue"; // import BodyContent from the BodyContent component
import FooterContent from "@/components/FooterContent.vue"; // import FooterContent from the FooterContent component

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
