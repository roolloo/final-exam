<template>
  <div class="conteiner">
    <div class="contact">
      <div class="contact__text">
        <h2 class="contact-text__title">DELICIOUS MENU</h2>
        <p class="contact-text__paragraph">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis at velit
          maximus, molestie est a, tempor magna.
        </p>
      </div>
      <form class="contact__form" action="/" method="post">
        <div class="contact-form__conteiner">
          <input
            class="contact-form__inp"
            type="text"
            name="name"
            placeholder="Name"
          />
          <input
            class="contact-form__inp"
            type="text"
            name="email"
            placeholder="Emaile"
          />
          <input
            class="contact-form__inp"
            type="tel"
            name="phone"
            placeholder="Phone"
          />
          <textarea
            class="contact-form__inp textarea__contact"
            name=""
            id=""
            cols="30"
            rows="10"
            placeholder="Messeg"
          ></textarea>
        </div>
        <div class="contact-form__conteiner2">
          <p class="contact__info">
            <i class="fas contact-info__icon fa-map-marker-alt"></i> 5th London
            Boulevard, U.K. <i class="fas contact-info__icon fa-phone"></i> +40
            729 131 637/+40 726 458 782
            <i class="fas contact-info__icon fa-envelope"></i>
            office@mindblister.com
          </p>
          <button class="contact__btn">SEND MESSAGE</button>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "appcontact",
  data() {},
};
</script>

<style lang="sass">
@import './sass/contact'
</style>