<template>
  <div class="flex flex-col min-h-screen font-Roboto bg-weather-primary">
    <SiteNavigation />
    <RouterView />
  </div>
</template>
<script>
import { RouterView } from "vue-router";
import SiteNavigation from "./components/SiteNavigation.vue";

export default {
  name: "App",
  components: {
    SiteNavigation,
  },
};
</script>

<style lang="scss" scoped></style>
