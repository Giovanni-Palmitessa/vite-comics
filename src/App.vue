<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";

export default {
  components: {
    AppHeader,
    AppMain,
  },
};
</script>

<template>
  <div class="container">
    <AppHeader />
    <AppMain />
  </div>
</template>

<style lang="scss">
@use "./assets/styles/general.scss" as *;

.container {
  max-width: 1000px;
  margin-inline: auto;
}
</style>
