<template>
  <div class="dc-background">
      <div class="container row">
        <div>
            <img src="../assets/img/buy-comics-digital-comics.png" alt="digital comics">
            <div class="font-white">DIGITAL COMICS</div>
        </div> 
        <div>
            <img src="../assets/img/buy-comics-merchandise.png" alt="merchandise">
            <div class="font-white">DS MERCHANDISE</div>
        </div> 
        <div>
            <img src="../assets/img/buy-comics-subscriptions.png" alt="subscription">
            <div class="font-white">SUBSCRIPTION</div>
        </div> 
        <div>
            <img src="../assets/img/buy-comics-shop-locator.png" alt="shop locator">
            <div class="font-white">COMICS SHOP LOCATOR</div>
        </div> 
        <div>
            <img src="../assets/img/buy-dc-power-visa.svg" alt="ds power visa">
            <div class="font-white">DS POWER VISA</div>
        </div> 
      </div>
  </div>
</template>

<script>
export default {
    name: 'Nav',
}
</script>

<style scoped>
    .row {
        justify-content: space-between;
    }

    .row img {
        padding: 30px 8px 30px 0;
        width: 40px;
    }

    .row :nth-last-child(2) img{
        width: 30px;
    }

    .row div {
        display: flex;
        align-items: center;
        font-size: 0.8rem;
    }
</style>