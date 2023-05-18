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
      <div class="footer-content">
        <div class="footer-links">
          <ul class="ul-option">
            <li class="option">
              DC COMICS
              <ul class="ul-sub-option">
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
              <ul class="ul-sub-option">
                <li class="sub-option">Terms Of Use</li>
                <li class="sub-option">Privacy Policy (New)</li>
                <li class="sub-option">Ad Choises</li>
                <li class="sub-option">Advertising</li>
                <li class="sub-option">Jobs</li>
                <li class="sub-option">Subscriptions</li>
                <li class="sub-option">Talent Workshop</li>
                <li class="sub-option">CPSC Certificates</li>
                <li class="sub-option">Ratings</li>
                <li class="sub-option">Shop Help</li>
                <li class="sub-option">Contact Us</li>
              </ul>
            </li>

            <li class="option">
              SITES
              <ul class="ul-sub-option">
                <li class="sub-option">DC</li>
                <li class="sub-option">MAD Magazine</li>
                <li class="sub-option">DC Kids</li>
                <li class="sub-option">DC Universe</li>
                <li class="sub-option">DC Power Visa</li>
              </ul>
            </li>
          </ul>
        </div>

        <div class="big-logo">
          <img src="../assets/img/dc-logo-bg.png" alt="Dc logo big" />
        </div>
      </div>
    </div>
  </div>

  <div class="additional-footer">
    <div class="container">
      <div class="additional-content">
        <div class="sign-up">SIGN UP NOW!</div>

        <div class="socials">
          <span>FOLLOW US</span>

          <img src="..//assets/img/footer-facebook.png" alt="Facebook" />

          <img src="..//assets/img/footer-twitter.png" alt="Youtube" />
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

.footer-content {
  display: flex;
  justify-content: space-between;
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
  padding: 2rem;
}

.option {
  color: $white;
  font-size: 1rem;
  font-weight: 700;
}

.ul-option {
  display: flex;
  gap: 3rem;
}

.ul-sub-option {
  display: flex;
  flex-direction: column;
  gap: 5px;
}

.sub-option {
  color: $gray;
  font-size: 0.6rem;
}
</style>
