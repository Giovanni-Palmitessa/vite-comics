<script>
import AppHeader from "./components/AppHeader.vue";

export default {
  components: {
    AppHeader,
  },
};
</script>

<template>
  <div class="container">
    <AppHeader />
  </div>
</template>

<style lang="scss">
@use "./assets/styles/general.scss" as *;

.container {
  max-width: 1000px;
  margin-inline: auto;
}
</style>
