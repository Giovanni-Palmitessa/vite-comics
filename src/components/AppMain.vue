<script>
export default {};
</script>
<template>
  <main>
    <div class="container">
      <div class="main-content">Contents goes here!</div>
    </div>
  </main>
</template>

<style lang="scss" scoped>
@use "../assets/styles/partials/variables" as *;

.container {
  max-width: 1000px;
  margin-inline: auto;
}

main {
  background-color: $black;
  height: 200px;
  color: $white;
  font-size: 2rem;
  font-weight: 600;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
