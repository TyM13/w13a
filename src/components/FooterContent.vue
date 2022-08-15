<template>
  <footer>                                                                 
    <a href="https://en.wikipedia.org/wiki/Cheetah">More Cheetah Info</a>
  </footer>
</template>

<script>                  //(wont let me comment in most places)styles content only for the footer component
export default {          
  name: "footer-content",
};
</script>                 
                          

<style scoped>            
footer {
  display: grid;
  grid-column: 1fr;
  place-items: center;
}

a {
  text-align: center;
  margin: 100px;
  border: 2px solid sandybrown;
  width: 150px;
  padding: 10px;
}
</style> 