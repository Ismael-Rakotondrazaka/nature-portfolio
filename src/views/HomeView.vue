<template>
  <TheAside />
  <div class="px-2" style="margin-left: calc(300px)" id="main">
    <ThePortfolioSection />
    <TheAboutSection />
    <TheContactSection />
    <TheFooter />
  </div>
</template>

<script>
import TheAside from "@/components/TheAside.vue";
import ThePortfolioSection from "@/components/ThePortfolioSection.vue";
import TheAboutSection from "@/components/TheAboutSection.vue";
import TheContactSection from "@/components/TheContactSection.vue";
import TheFooter from "@/components/TheFooter.vue";

export default {
  name: "TheHomePage",
  components: {
    TheAside,
    ThePortfolioSection,
    TheAboutSection,
    TheContactSection,
    TheFooter,
  },
};
</script>

<style>
@media screen and (max-width: 992px) {
  #main {
    margin-left: 0 !important;
  }
}
</style>
