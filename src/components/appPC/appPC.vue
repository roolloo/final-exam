<template>
  <appheader></appheader>
  <appabout></appabout>
  <appTeam></appTeam>
  <appbook></appbook>
</template>

<script>
import appheader from "./components/appheader.vue";
import appabout from "./components/appabout.vue";
import appTeam from "./components/appTeam.vue";
import appbook from "./components/appbook.vue";
export default {
  name: "appPc",
  components: {
    appheader,
    appabout,
    appTeam,
    appbook,
  },
};
</script>
