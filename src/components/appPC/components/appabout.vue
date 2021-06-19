<template>
  <div class="conteiner">
    <section class="about">
      <div class="about__text">
        <h2 class="about-text__title">about us</h2>
        <p class="about-text__paragraph">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis at velit
          maximus, molestie est a, tempor magna.
        </p>
        <div class="about-text__content">
          Integer ullamcorper neque eu purus euismod, ac faucibus mauris
          posuere. Morbi non ultrices ligula. Sed dictum, enim sed ullamcorper
          feugiat, dui odio vehicula eros, a sollicitudin lorem quam nec sem.
          Mauris tincidunt feugiat diam convallis pharetra. Nulla facilisis
          semper laoreet.
        </div>
      </div>
      <div class="about__img">
        <img class="about-img__ad" src="./assetsPC/about-img.png" alt="/" />
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "appabout",
  data() {},
};
</script>

<style lang="sass">
@import './sass/about'
</style>