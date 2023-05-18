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

  <div class="bottom-footer">
    <div class="container">
      <div class="footer-links">
        <ul>
          <li class="option">
            DC COMICS
            <ul>
              <li class="sub-option">Character</li>
              <li class="sub-option">Comics</li>
              <li class="sub-option">Movies</li>
              <li class="sub-option">TV</li>
              <li class="sub-option">Games</li>
              <li class="sub-option">Videos</li>
              <li class="sub-option">News</li>
            </ul>
          </li>

          <li class="option">
            DC
            <ul>
              <li class="sub-option">Character</li>
              <li class="sub-option">Comics</li>
              <li class="sub-option">Movies</li>
              <li class="sub-option">TV</li>
              <li class="sub-option">Games</li>
              <li class="sub-option">Videos</li>
              <li class="sub-option">News</li>
            </ul>
          </li>
        </ul>
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

.bottom-footer {
  background-image: url(../assets/img/footer-bg.jpg);
  background-size: cover;
}

.option {
  color: $white;
  font-size: 1rem;
  font-weight: 700;
}
.sub-option {
  color: $gray;
  font-size: 0.6rem;
}
</style>
