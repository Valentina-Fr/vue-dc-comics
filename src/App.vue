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
    <Footer/>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Content from '@/components/Content.vue';
import Dc from '@/components/Dc.vue';
import Footer from '@/components/Footer.vue';
export default {
  name: 'App',
  components: {
    Header,
    Content,
    Dc,
    Footer,
  }
}
</script>

<style lang="scss">
@import "@/assets/scss/style.scss";
</style>
