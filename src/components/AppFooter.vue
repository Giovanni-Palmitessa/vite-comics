<script>
export default {};
</script>
<template>
  <div class="top-footer">
    <div class="container">
      <div class="links">
        <div class="link">
          <img src="../assets/img/buy-comics-digital-comics.png" />
          <span>DIGITAL COMICS</span>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../assets/styles/partials/variables" as *;

.top-footer {
  padding: 1rem;
  background-color: $main-color;
  color: $white;
}
.container {
  max-width: 1000px;
  margin-inline: auto;
}

.links {
  display: flex;
  align-items: center;
}

.link {
  display: flex;
  align-items: center;
  gap: 10px;
}

.link img {
  width: 25%;
}
</style>
