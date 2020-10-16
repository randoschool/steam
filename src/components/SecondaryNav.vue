<template>
  <div
    class="flex bg-secondary-nav shadow-lg max-w-5xl mx-auto mt-10 text-sm font-light"
  >
    <sec-nav-button>Sinu Pood</sec-nav-button>
    <sec-nav-button>Sirvi</sec-nav-button>
    <sec-nav-button>Punktide Pood</sec-nav-button>
    <sec-nav-button>Uudised</sec-nav-button>
    <sec-nav-button>Labor</sec-nav-button>
    <div
      class="ml-auto self-center mr-1 border border-gray-800 bg-secondary-nav rounded-sm"
    >
      <input
        type="text"
        name="search"
        class="leading-7 px-1 text-gray-300 font-light italic mt-1 bg-transparent"
        placeholder="Otsi poest..."
      />
    </div>
  </div>
</template>
<script>
import SecNavButton from "./SecNavButton.vue";
export default {
  components: {
    SecNavButton,
  },
};
</script>
