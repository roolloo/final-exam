<template>
  <section class="book">
    <div class="conteiner">
      <div class="book__fix">
        <div>
          <h2 class="book-text__title">book a table</h2>
          <form class="book__form" action="/" method="post">
            <div class="form__left">
              <input
                class="book-form__inp"
                type="text"
                name="name"
                placeholder="Name"
              />
              <input
                class="book-form__inp"
                type="tel"
                name="phone"
                placeholder="Phone"
              />
              <input
                class="book-form__inp"
                type="text"
                name="date"
                placeholder="Date (mm/dd)"
              />
            </div>
            <div class="form__right">
              <input
                class="book-form__inp"
                type="email"
                name="email"
                placeholder="Email"
              />
              <div class="form-right__peopl">
                <input
                  @click="openlist()"
                  type="text"
                  name="pipol"
                  placeholder="People"
                  v-bind:value="msp"
                  class="book-form__inp pip"
                  readonly
                /><i class="fas arrow__form2 fa-angle-down"></i>
                <ul class="list__pip" v-if="seen">
                  <li
                    class="pipol__item"
                    @click="nam(todo)"
                    v-for="todo in todos"
                    :key="todo.nam"
                  >
                    {{ todo.nam }}
                  </li>
                </ul>
              </div>
              <div class="form-right__time">
                <input
                  @click="openlist2()"
                  type="text"
                  name="time"
                  placeholder="Time"
                  v-bind:value="msp2"
                  class="book-form__inp time"
                  readonly
                /><i class="fas arrow__form2 fa-angle-down"></i>
                <ul class="list__time" v-if="seen2">
                  <li
                    class="time__item"
                    @click="nam2(tod)"
                    v-for="tod in todos2"
                    :key="tod.nam2"
                  >
                    {{ tod.nam2 }}
                  </li>
                </ul>
              </div>
            </div>
            <button class="book-form__btn">BOOK NOW</button>
          </form>
        </div>
        <div class="book__img">
          <img class="book-img__ad" src="./assetsPC/about.png" alt="/" />
        </div>
      </div>
      <p class="book__data">
        Mon - Fri: 8PM - 10PM, Sat - Sun: 8PM - 3AM, Phone: +40 729 131 637/+40
        726 458 782
      </p>
    
    </div>
	
  </section>
</template>

<script>
export default {
  name: "appbook",
  data() {
    return {
      seen: false,
      seen2: false,
      todos: [{ nam: "1" }, { nam: "2" }, { nam: "3" }, { nam: "4" }],
      todos2: [{ nam2: "1" }, { nam2: "2" }, { nam2: "3" }, { nam2: "4" }],
      msp: "",
    };
  },
  methods: {
    openlist() {
      return (this.seen = true), (this.seen2 = false);
    },
    openlist2() {
      return (this.seen2 = true), (this.seen = false);
    },
    nam(todo) {
      return (this.msp = todo.nam), (this.seen = false);
    },
    nam2(tod) {
      return (this.msp2 = tod.nam2), (this.seen2 = false);
    },
  },
};
</script>

<style lang="sass">
@import './sass/book'
</style>