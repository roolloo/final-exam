<template>
  <swiper
    class="slider"
    :slides-per-view="1"
    :space-between="50"
    navigation
    :pagination="{ clickable: true }"
    @swiper="onSwiper"
    @slideChange="onSlideChange"
  >
    <swiper-slide class="slide">
      <div class="conteiner">
        <h3 class="slide__title">
          <span class="swiper-no-swiping">OUR TEAM</span>
        </h3>

        <div class="slide__fix">
          <div class="slide__img">
            <span class="swiper-no-swiping">
              <img src="./assetsPC/Rectangle2.png" alt="/"
            /></span>
          </div>
          <div class="slide__text">
            <h2 class="slide-text__title">
              <span class="swiper-no-swiping">MASTER CHEF</span>
            </h2>
            <p class="slide-text__paragraph">
              <span class="swiper-no-swiping">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis at
                velit maximus, molestie est a, tempor magna.</span
              >
            </p>
            <div class="slide-text__content">
              <span class="swiper-no-swiping">
                Integer ullamcorper neque eu purus euismod, ac faucibus mauris
                posuere. Morbi non ultrices ligula. Sed dictum, enim sed
                ullamcorper feugiat, dui odio vehicula eros, a sollicitudin
                lorem quam nec sem. Mauris tincidunt feugiat diam convallis
                pharetra. Nulla facilisis semper laoreet.</span
              >
            </div>
          </div>
        </div>
      </div>
    </swiper-slide>
    <swiper-slide class="slide"
      ><div class="conteiner">
        <h3 class="slide__title">
          <span class="swiper-no-swiping">OUR TEAM</span>
        </h3>

        <div class="slide__fix">
          <div class="slide__img">
            <span class="swiper-no-swiping">
              <img src="./assetsPC/Rectangle2.png" alt="/"
            /></span>
          </div>
          <div class="slide__text">
            <h2 class="slide-text__title">
              <span class="swiper-no-swiping">MASTER CHEF</span>
            </h2>
            <p class="slide-text__paragraph">
              <span class="swiper-no-swiping">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis at
                velit maximus, molestie est a, tempor magna.</span
              >
            </p>
            <div class="slide-text__content">
              <span class="swiper-no-swiping">
                Integer ullamcorper neque eu purus euismod, ac faucibus mauris
                posuere. Morbi non ultrices ligula. Sed dictum, enim sed
                ullamcorper feugiat, dui odio vehicula eros, a sollicitudin
                lorem quam nec sem. Mauris tincidunt feugiat diam convallis
                pharetra. Nulla facilisis semper laoreet.</span
              >
            </div>
          </div>
        </div>
      </div></swiper-slide
    >
    <swiper-slide class="slide"
      ><div class="conteiner">
        <h3 class="slide__title">
          <span class="swiper-no-swiping">OUR TEAM</span>
        </h3>

        <div class="slide__fix">
          <div class="slide__img">
            <span class="swiper-no-swiping">
              <img src="./assetsPC/Rectangle2.png" alt="/"
            /></span>
          </div>
          <div class="slide__text">
            <h2 class="slide-text__title">
              <span class="swiper-no-swiping">MASTER CHEF</span>
            </h2>
            <p class="slide-text__paragraph">
              <span class="swiper-no-swiping">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis at
                velit maximus, molestie est a, tempor magna.</span
              >
            </p>
            <div class="slide-text__content">
              <span class="swiper-no-swiping">
                Integer ullamcorper neque eu purus euismod, ac faucibus mauris
                posuere. Morbi non ultrices ligula. Sed dictum, enim sed
                ullamcorper feugiat, dui odio vehicula eros, a sollicitudin
                lorem quam nec sem. Mauris tincidunt feugiat diam convallis
                pharetra. Nulla facilisis semper laoreet.</span
              >
            </div>
          </div>
        </div>
      </div></swiper-slide
    >
    ...
  </swiper>
</template>

<script>
import SwiperCore, {
  Navigation,
  EffectCube,
  Pagination,
  Scrollbar,
  A11y,
} from "swiper";

// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/swiper.scss";
import "swiper/components/navigation/navigation.scss";
import "swiper/components/pagination/pagination.scss";
import "swiper/components/scrollbar/scrollbar.scss";
import "swiper/components/effect-cube/effect-cube.min.css";

// install Swiper modules
SwiperCore.use([Navigation, EffectCube, Pagination, Scrollbar, A11y]);

// Import Swiper styles
export default {
  name: "appslider",
  components: {
    Swiper,
    SwiperSlide,
  },
  methods: {
    onSwiper(swiper) {
      console.log(swiper);
    },
    onSlideChange() {
      console.log("slide change");
    },
  },
};
</script>

<style lang="sass">
@import './sass/slide'
</style>