<template>
  <carousel-3d :width="512" :height="512" :autoplay="true" :autoplay-timeout="1000" :display="3">
    <slide :index="0"><div class="slide slide--0"></div></slide>
    <slide :index="1"><div class="slide slide--1"></div></slide>
    <slide :index="2"><div class="slide slide--2"></div></slide>
    <slide :index="3"><div class="slide slide--3"></div></slide>
    <slide :index="4"><div class="slide slide--4"></div></slide>
    <slide :index="5"><div class="slide slide--5"></div></slide>
    <slide :index="6"><div class="slide slide--6"></div></slide>
    <slide :index="7"><div class="slide slide--7"></div></slide>
    <slide :index="8"><div class="slide slide--8"></div></slide>
    <slide :index="9"><div class="slide slide--9"></div></slide>
  </carousel-3d>
</template>

<script>
  import { Carousel3d, Slide } from 'vue-carousel-3d';

  export default {
    name: 'Carousel',
    components: {
      Carousel3d,
      Slide
    },
  };
</script>

<style lang="scss">
.slide {
  width: 100%;
  height: 100%;
  background-size: cover;
  &--0 { background-image: url('../assets/images/carousel/image_0.webp'); }
  &--1 { background-image: url('../assets/images/carousel/image_1.webp'); }
  &--2 { background-image: url('../assets/images/carousel/image_2.webp'); }
  &--3 { background-image: url('../assets/images/carousel/image_3.webp'); }
  &--4 { background-image: url('../assets/images/carousel/image_4.webp'); }
  &--5 { background-image: url('../assets/images/carousel/image_5.webp'); }
  &--6 { background-image: url('../assets/images/carousel/image_6.webp'); }
  &--7 { background-image: url('../assets/images/carousel/image_7.webp'); }
  &--8 { background-image: url('../assets/images/carousel/image_8.webp'); }
  &--9 { background-image: url('../assets/images/carousel/image_9.webp'); }
}
</style>