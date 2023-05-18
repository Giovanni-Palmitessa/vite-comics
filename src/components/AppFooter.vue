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

        <div class="link">
          <img src="../assets/img/buy-comics-merchandise.png" />
          <span>DC MERCHANDISE</span>
        </div>

        <div class="link">
          <img src="../assets/img/buy-comics-subscriptions.png" />
          <span>SUBSCRIPTION</span>
        </div>

        <div class="link">
          <img src="../assets/img/buy-comics-shop-locator.png" />
          <span>COMIC SHOP LOCATOR</span>
        </div>

        <div class="link">
          <img src="../assets/img/buy-dc-power-visa.svg" />
          <span>DC POWER VISA</span>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../assets/styles/partials/variables" as *;

.top-footer {
  padding: 2rem 1rem;
  background-color: $main-color;
  color: $white;
  font-size: 10px;
}
.container {
  max-width: 1000px;
  margin-inline: auto;
}

.links {
  display: flex;
  justify-content: space-between;
}

.link {
  display: flex;
  align-items: center;
  gap: 10px;
}

.link img {
  width: 50px;
}
</style>
