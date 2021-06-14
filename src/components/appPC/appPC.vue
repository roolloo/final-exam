<template>
  <appheader></appheader>
  <appabout></appabout>
  <appTeam></appTeam>
  <appbook></appbook>
  <appslider></appslider>
</template>

<script>
import appheader from "./components/appheader.vue";
import appabout  from "./components/appabout.vue";
import appTeam   from "./components/appTeam.vue";
import appbook   from "./components/appbook.vue";
import appslider from "./components/appslider.vue";
export default {
  name: "appPc",
  components: {
    appheader,
    appabout,
    appTeam,
    appbook,
    appslider,
  },
};
</script>
