<template>
  <div>
    <home-carousel />
    <home-info />
    <page-footer />
  </div>
</template>

<style>
</style>

<script>
import HomeCarousel from "components/HomeCarousel.vue";
import HomeInfo from "components/HomeInfo.vue";
import PageFooter from "components/PageFooter.vue";
export default {
  components: {
    HomeCarousel,
    HomeInfo,
    PageFooter
  },
  name: "PageIndex",
  methods: {
    getStyle() {
      return { color: "white" };
    }
  }
};
</script>