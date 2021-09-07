<template>
  <div id="app">
    <Header/>
    <main>
      <section>
        <Content/>
      </section>
      <section>
        <Nav/>
      </section>
      <section>
        <Dc/>
      </section>
    </main>
    <Footer/>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Content from '@/components/Content.vue';
import Dc from '@/components/Dc.vue';
import Footer from '@/components/Footer.vue';
import Nav from '@/components/Nav.vue';
export default {
  name: 'App',
  components: {
    Header,
    Content,
    Dc,
    Footer,
    Nav
  }
}
</script>

<style lang="scss">
@import "@/assets/scss/style.scss";
</style>
