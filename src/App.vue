<template>
  <appPC></appPC>
</template>

<script>
import appPC from "./components/appPC/appPC.vue";

export default {
  name: "App",
  components: {
    appPC,
  },
};
</script>

<style lang="scss">
body {
  background: #fff;
  margin: 0 auto;
  width: 100%;
  max-width: 100%;
}
ul{
	margin: 0;
	padding: 0;
}
</style>


