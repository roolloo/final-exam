<template>
  <div class="conteiner">
    <div class="menu">
      <div class="menu__text">
        <h2 class="menu-text__title">DELICIOUS MENU</h2>
        <p class="menu-text__paragraph">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis at velit
          maximus, molestie est a, tempor magna.
        </p>
      </div>
      <div class="menu__content">
        <ul class="menu__items">
          <li @click="onClick1()" class="menu-items__item">SOUPE</li>
          <li @click="onClick2()" class="menu-items__item">PIZZA</li>
          <li @click="onClick3()" class="menu-items__item">PASTA</li>
          <li @click="onClick4()" class="menu-items__item">DESERT</li>
          <li @click="onClick5()" class="menu-items__item">WINE</li>
          <li @click="onClick6()" class="menu-items__item">BEER</li>
          <li @click="onClick7()" class="menu-items__item" style="border: none">
            DRINKS
          </li>
        </ul>
        <div class="menu__conteiner">
          <ul class="menu-conteiner__items">
            <li
              class="conteiner-items__item"
              v-for="Arre in Arr"
              :key="(Arre.text, Arre.paragraph, Arre.zena)"
            >
              <p class="menu-conteiner__title">
                {{ text }} {{ Arre.paragraph }} . . . {{ Arre.zena }}
              </p>
              <div class="menu-conteiner__text">{{ Arre.text }}</div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "appmenu",
  data() {
    return {
      text: "",
      Arr: [
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
        {
          paragraph: " QUATRO STAGIONI",
          zena: "55,68 USD",
          text: "Integer ullamcorper neque eu purus euismod",
        },
      ],
    };
  },
  methods: {
    onClick1() {
      return (this.text = "SOUP");
    },
    onClick2() {
      return (this.text = "PIZZA");
    },
    onClick3() {
      return (this.text = "PASTA");
    },
    onClick4() {
      return (this.text = "DESERT");
    },
    onClick5() {
      return (this.text = "WINE");
    },
    onClick6() {
      return (this.text = "BEER");
    },
    onClick7() {
      return (this.text = "DRINKS");
    },
  },
};
</script>

<style lang="sass">
@import './sass/menu'
</style>