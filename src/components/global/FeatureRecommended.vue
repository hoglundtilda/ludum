<template>
  <section class="featured__section wrapper">
    <h3>FEATURE & RECOMMENDED</h3>
      <div>
      <img class="hero_bg" src="https://cdnb.artstation.com/p/assets/images/images/007/125/443/large/joshua-brian-smith-ornn-base-splash-web2.jpg?1503879061" alt="">
      <img class="logo" src="@/assets/lol.png" alt="">
      </div>
      <img class="feature__selector" src="@/assets/feature_selector.png" alt="">
  </section>
</template>

<script>
export default {
  data() {
    return {

    }
  }
}
</script>

<style lang="scss" scoped>
  .hero_bg {
    z-index: -1;
    position: relative;
    width: 100%;
    height: 500px;
    object-position: center;
    object-fit: cover;
    border-radius: $border_radius;
    box-shadow: $small_card_box_shadow;
  }



  .feature__selector {
    display: block;
    margin:auto;
    width: auto;
    height: 15px;
    transform: translateY(-30px);
  }

  .logo {
    z-index: -1;
    width: 20%;
    height: auto;
    position: absolute;
    top:50%;
    left:50%;
    transform: translate(-50%,-50%);
  }

  .featured__section {
    position: relative;
  }

  @media only screen and (max-width: 700px) {
     .hero_bg {
      height: 250px;
    }
    .feature__selector  {
      height: 8px;
    }
  .logo {
    height: 50px;
    width: auto;
  }
  }

</style>