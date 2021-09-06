<template>
  <div id="app">
    <Header></Header>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
export default {
  name: 'App',
  components: {
    Header,
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  max-width: 960px;
  margin: 0 auto;
}

img {
  max-width: 100%;
}

a {
  text-decoration: none;
  padding: 0 5px;
  color: darkgray;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
