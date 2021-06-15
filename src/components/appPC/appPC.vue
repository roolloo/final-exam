<template>
  <appheader></appheader>
  <appabout></appabout>
  <appTeam></appTeam>
  <appbook></appbook>
  <appslider></appslider>
  <appmenu></appmenu>
  <appprivat></appprivat>
</template>

<script>
import appheader from "./components/appheader.vue";
import appabout from "./components/appabout.vue";
import appTeam from "./components/appTeam.vue";
import appbook from "./components/appbook.vue";
import appslider from "./components/appslider.vue";
import appmenu from "./components/appmenu.vue";
import appprivat from "./components/appprivat.vue";

export default {
  name: "appPc",
  components: {
    appheader,
    appabout,
    appTeam,
    appbook,
    appslider,
    appmenu,
    appprivat,
  },
};
</script>
