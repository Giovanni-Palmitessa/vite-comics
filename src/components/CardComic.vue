<script>
export default {
  props: {
    urlImg: String,
    series: String,
  },
};
</script>
<template>
  <div class="card">
    <img :src="urlImg" :alt="series" />
    <h6>{{ series }}</h6>
  </div>
</template>

<style lang="scss" scoped>
@use "../assets/styles/partials/variables" as *;
.card {
  width: calc((100% - 5rem) / 6);

  h6 {
    color: $gray;
  }
  img {
    width: 100%;
    aspect-ratio: 1 / 1;
  }
}
</style>
