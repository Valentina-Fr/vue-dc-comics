<template>
  <footer>
      <div class="container row">
        <div>
            <a class="font-white sign-up" href="#">SIGN UP NOW!</a>
        </div>
        <div class="row">
            <span class="font-dc">FOLLOW US</span>
            <div class="social">
                <a href="#"><img src="@/assets/img/footer-facebook.png" alt="facebook"></a>
                <a href="#"><img src="@/assets/img/footer-twitter.png" alt="twitter"></a>
                <a href="#"><img src="@/assets/img/footer-youtube.png" alt="youtube"></a>
                <a href="#"><img src="@/assets/img/footer-pinterest.png" alt="pinterest"></a>
                <a href="#"><img src="@/assets/img/footer-periscope.png" alt="periscope"></a>
            </div>
        </div>
      </div>
  </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped>
    footer {
        background-color: #303030;
    }

    .row {
        justify-content: space-between;
        align-items: center;
    }

    .row>*{
        padding: 10px 0;
    }

    .sign-up {
        padding: 8px; 
        border: 1px solid #0282f9;
    }

    .social * {
        padding-left: 8px;
    }
</style>