<template>
  <header class="header">
    <div class="conteiner">
      <nav class="header-navigation">
        <ul class="header-navigation__items">
          <li class="header-navigation">
            <a class="header-navigation__link" href="">HOME</a>
          </li>
          <li class="header-navigation">
            <a class="header-navigation__link" href="">ABOUT</a>
          </li>
          <li class="header-navigation">
            <a class="header-navigation__link" href="">TEAM</a>
          </li>
          <li class="header-navigation">
            <a class="header-navigation__link" href="">BOOKING</a>
          </li>
        </ul>
        <div class="header-navigstion__logo">
          <a href="#"><img src="./assetsPC/Vector.svg" alt="/" /></a>
        </div>
        <ul class="header-navigation__items">
          <li class="header-navigation__item">
            <a class="header-navigation__link" href="">MENU</a>
          </li>
          <li class="header-navigation__item">
            <a class="header-navigation__link" href="">GALERIE</a>
          </li>
          <li class="header-navigation__item">
            <a class="header-navigation__link" href="">EVENTS</a>
          </li>
          <li class="header-navigation__item">
            <a class="header-navigation__link" href="">CONTACT</a>
          </li>
        </ul>
      </nav>

      <div class="header__content">
        <div class="header-content__data">
          Mon - Fri: 8PM - 10PM, Sat - Sun: 8PM - 3AM
        </div>
        <div class="header-content__center">
          <p class="header-content__title">RESTAURANT</p>
          <h1 class="header-content__oglovlenie">hungry people</h1>

          <div class="header-content__btn">
            <button class="header-content__one btn">BOOK TABLE</button>
            <button class="header-content__tue btn">EXPLORE</button>
          </div>
          <a href="#" class="heaeder-content__arrow"> </a>
        </div>

        <div class="header__socual">
          <a href="" class="header-socual__link"
            ><i class="fab fa-facebook-f"></i
          ></a>
          <a href="" class="header-socual__link"
            ><i class="fab fa-twitter"></i
          ></a>
          <a href="" class="header-socual__link"
            ><i class="fab fa-instagram"></i
          ></a>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "appheader",
  data() {},
};
</script>

<style lang="sass">
@import './sass/header'
</style>