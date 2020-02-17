<template>
    <header>
        <span class="logo"><a href="/">Catmash</a></span>
    </header>    
</template>

<script>
export default {
  name: 'Header',
  components: {}
}
</script>

<style scoped>
header {
  display: flex;
  border-bottom: 1px solid black;
}
a {
  color: inherit;
  text-decoration: none;
}
.logo {
  font-size: 2em;
  font-weight: bold;
  /* line-height: 1em; */
  text-decoration: none;
}
</style>