<template>
  <header class="header">
    <div class="conteiner">
      <nav class="header-navigation">
        <ul class="header-navigation__items1">
          <li class="header-navigation">HOME</li>
          <li class="header-navigation">ABOUT</li>
          <li class="header-navigation">TEAM</li>
          <li class="header-navigation">BOOKING</li>
        </ul>
        <div class="header__logo">
          <img src="./assetsPC/Vector.svg" alt="/" />
        </div>
        <ul class="header-navigation__items2">
          <li class="header-navigation">MENU</li>
          <li class="header-navigation">GALERIE</li>
          <li class="header-navigation">EVENTS</li>
          <li class="header-navigation">CONTACT</li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "appheader",
  data() {},
};
</script>

<style lang="scss">
@import "./sass/header"

</style>