<template>
  <primary-nav />
  <div class="grid grid-cols-main px-32 mt-8 gap-4">
    <div>
      <side-bar />
    </div>
    <div>
      <secondary-nav />
    </div>
  </div>
</template>
<script>
import PrimaryNav from "./components/PrimaryNav.vue";
import SecondaryNav from "./components/SecondaryNav.vue";
import SideBar from "./components/Sidebar.vue";
export default {
  name: "App",
  components: {
    PrimaryNav,
    SecondaryNav,
    SideBar,
  },
};
</script>ˇ
<style src="./assets/tailwind.css" />
