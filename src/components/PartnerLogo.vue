<template>
  <!-- Partner Logo Section Begin -->
  <div class="partner-logo">
    <div class="container">
      <Carousel
        class="logo-carousel"
        :items="5"
        :loop="true"
        :autoplay="true"
        :dots="false"
        :nav="false"
      >
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-1.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-2.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-3.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-4.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-5.png" alt="" />
          </div>
        </div>
      </Carousel>
    </div>
  </div>
  <!-- Partner Logo Section End -->
</template>

<script>
import Carousel from "vue-owl-carousel";

export default {
  name: "PartnerLogo",
  components: { Carousel },
};
</script>