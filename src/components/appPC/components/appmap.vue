<template>
  <iframe
    src="https://yandex.ru/map-widget/v1/?um=constructor%3A8bb00f69ef3544efc870b94cb6aa1f47c5945d4facf186841bd6c232f6c8ef0d&amp;source=constructor"
    width="100%"
    height="475"
    frameborder="0"
  ></iframe>
</template>

<script>
export default {
  name: "appma",
  data() {
},
methods: {
	myMap.controls.remove('zoomControl')
}
}
</script>

<style lang="sass">
@import './sass/Team'
</style>