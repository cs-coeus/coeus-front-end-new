<template>
  <div class="app-wrapper">
    <nav-bar />
    <div>
      <hero-section />
      <features-section />
      <how-it-works-section />
      <about-us-section />
      <footer-section />
    </div>
  </div>
</template>

<script lang="ts">
import NavBar from "./components/ui/NavBar.vue";
import HeroSection from "./components/MainPage/HeroSection.vue";
import FeaturesSection from "./components/MainPage/FeaturesSection.vue";
import HowItWorksSection from "./components/MainPage/HowItWorksSection.vue";
import AboutUsSection from "./components/MainPage/AboutUsSection.vue";
import FooterSection from "./components/ui/FooterSection.vue";

export default {
  name: "App",
  components: {
    NavBar,
    HeroSection,
    FeaturesSection,
    HowItWorksSection,
    AboutUsSection,
    FooterSection,
  },
};
</script>

<style scoped>
.app-wrapper {
  padding: 0 96px;
}

@media only screen and (max-width: 986px) {
  .app-wrapper {
    padding: 0 48px;
  }
}
</style>
