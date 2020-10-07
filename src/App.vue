<template>
  <primary-nav />
  <secondary-nav />
</template>
<script>
import PrimaryNav from "./components/PrimaryNav.vue";
import SecondaryNav from "./components/SecondaryNav.vue";

export default {
  name: "App",
  components: {
    PrimaryNav,
    SecondaryNav,
  },
};
</script>ˇ
<style src="./assets/tailwind.css" />
