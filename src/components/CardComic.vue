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
    <h4>{{ series }}</h4>
  </div>
</template>

<style lang="scss" scoped>
.card {
  width: calc((100% - 5rem) / 6);
  img {
    width: 100%;
    aspect-ratio: 1 / 1;
  }
}
</style>
