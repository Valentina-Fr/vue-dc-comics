<template>
  <div class="container">
    <div class="row">
        <div class="col-4">
            <img src="../assets/img/dc-logo.png" alt="logo" id="logo">
        </div>
        <div class="col-8">
            <ul>
                <li :class="{ active: link.current }" v-for="(link, index) in links" :key="index"><a :href="link.url">{{link.text}}</a></li>
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

<style scoped lang="scss">
  @import "../assets/scss/_vars.scss";
    .row {
        align-items: center;
    }

    .col-8 {
        width: calc(100% / 12 * 8);
    }

    .col-4{
        width: calc(100% / 12 * 4);
    }

    ul {
        display: flex;
        text-transform: uppercase;
    }

    li {
      padding: 50px 5px;
      margin-top: 3px;
      a {
        font-weight: bold;
        font-size: 0.8rem;
        color: #4e585f;
      }
    }

    .active a {
      color: $dc-color;
    }

    .active {
      border-bottom: 3px solid $dc-color;
    }
    
</style>