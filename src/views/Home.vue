<template>
  <navbar></navbar>
  <!-- Hero -->
  <hero></hero>

  <!-- Branding -->
  <branding></branding>

  <!-- Achievements -->
  <achievements></achievements>
</template>

<script>
import Navbar from "../components/Navbar.vue";
import Hero from "../components/Hero.vue";
import Branding from "../components/Branding.vue";
import Achievements from "../components/Achievements.vue";
export default {
  components: {
    Navbar,
    Hero,
    Branding,
    Achievements,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  line-height: 1.3;
}
</style>
