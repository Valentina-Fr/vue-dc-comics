<template>
  <div class="container">
    <div class="row">
        <div class="col-4">
            <img src="@/assets/img/dc-logo.png" alt="logo" id="logo">
        </div>
        <div class="col-8">
            <ul>
                <li v-for="(link, index) in links" :key="index"><a :href="link.url">{{link.text}}</a></li>
            </ul>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Header',
    data(){
        return {
            links: [
  {
    text: 'Characters',
    url: '#',
    current: false,
  },
  {
    text: 'Comics',
    url: '#',
    current: true,
  },
  {
    text: 'Movies',
    url: '#',
    current: false,
  },
  {
    text: 'TV',
    url: '#',
    current: false,
  },
  {
    text: 'Games',
    url: '#',
    current: false,
  },
  {
    text: 'Collectibles',
    url: '#',
    current: false,
  },
  {
    text: 'Videos',
    url: '#',
    current: false,
  },
  {
    text: 'Fans',
    url: '#',
    current: false,
  },
  {
    text: 'News',
    url: '#',
    current: false,
  },
  {
    text: 'Shop',
    url: '#',
    current: false,
  },
]
        }
    }
}
</script>

<style scoped>
    .row {
        display: flex;
        align-items: center;
    }

    .col-8 {
        width: calc(100% / 12 * 8);
    }

    .col-4{
        width: calc(100% / 12 * 4);
    }

    #logo {
        padding: 10px 0;
    }

    ul {
        list-style: none;
        display: flex;
        text-transform: uppercase;
    }
    
</style>