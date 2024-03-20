<template>
  <header class="sticky top-0 bg-weather-primary shadow-lg">
    <nav
      class="container flex flex-col sm:flex-row items-center gap-4 text-[white] p-6"
    >
      <RouterLink :to="{ home }">
        <div class="flex items-center gap-3 flex-l">
          <i class="fa-solid fa-sun text-2xl"></i>
          <p class="text-2xl">The Local Weather</p>
        </div>
      </RouterLink>
    </nav>
  </header>
</template>

<script>
import { RouterLink } from "vue-router";
export default {
  name: "SiteNavigation",
};
</script>
