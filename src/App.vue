<template>
  <div id="app">
    <Header/>
    <main>
      <section>
        <Content/>
      </section>
      <section>
        <Dc/>
      </section>
    </main>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Content from '@/components/Content.vue';
import Dc from '@/components/Dc.vue'
export default {
  name: 'App',
  components: {
    Header,
    Content,
    Dc,
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
  color: darkgray;
}

ul {
  list-style: none;
}

.row {
  display: flex;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
