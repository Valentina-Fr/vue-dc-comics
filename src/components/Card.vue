<template>
  <figure id="card">
    <img :src="serie.thumb" :alt="serie.series"> 
    <figcaption>{{ serie.series }}</figcaption>
  </figure>
</template>

<script>
export default {
    name: 'Card',
    props: ['serie']
}
</script>

<style scoped lang="scss">
    #card {
        width: 120px;
        margin: 20px;
        figcaption {
            font-size: 0.8rem;
            text-transform: uppercase;
        }
    }
</style>