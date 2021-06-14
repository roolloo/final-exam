<template>
  <section class="book">
    <div class="conteiner">
      <div class="team__fix">
        <div class="team__text">
          <h2 class="team-text__title">MASTER CHEF</h2>
          <form action="/" method="post">
            <input type="text" name="name" placeholder="Name" />
            <input type="tel" name="phone" placeholder="Phone" />
            <input type="text" name="date" placeholder="Date" />
            <input type="email" name="email" placeholder="Email" />
            <input type="text" name="pipol" placeholder="People">
            <input type="text" name="time" placeholder="Time">
          </form>
        </div>
        <div class="team__img">
          <img src="./assetsPC/about.png" alt="/" />
        </div>
      </div>
      <p class="data"></p>
    </div>
  </section>
</template>

<script>
export default {
  name: "appbook",
  data() {
   
  },
};
</script>

<style lang="sass">
@import './sass/book'
</style>