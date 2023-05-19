<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFooter from "./components/AppFooter.vue";
import CardComic from "./components/CardComic.vue";

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    CardComic,
  },
};
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
</template>

<style lang="scss">
@use "./assets/styles/general.scss" as *;
</style>
