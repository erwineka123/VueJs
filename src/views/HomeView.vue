<template>
  <div class="home">
    <NavigationBar />
    <div class="container">
      <HeroBanner />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import NavigationBar from "@/components/NavigationBar.vue";
import HeroBanner from "@/components/Hero.vue";

export default {
  name: "HomeView",
  components: {
    NavigationBar,
    HeroBanner,
  },
};
</script>
