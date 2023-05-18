<script>
export default {};
</script>
<template>
  <header>
    <div class="container">
      <div class="navbar">
        <div class="logo">
          <img src="../assets/img/dc-logo.png" alt="Dc Logo" />
        </div>

        <div class="choose">
          <ul>
            <li><a>Characters</a></li>
            <li><a>Comics</a></li>
            <li><a>Movies</a></li>
            <li><a>TV</a></li>
            <li><a>Games</a></li>
            <li><a>Collectibles</a></li>
            <li><a>Videos</a></li>
            <li><a>Fans</a></li>
            <li><a>News</a></li>
            <li><a>Shop</a></li>
          </ul>
        </div>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
.container {
  max-width: 1000px;
  margin-inline: auto;
}
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 1rem;
  margin-bottom: 1rem;
}
.logo {
  display: flex;
}

.choose ul {
  list-style: none;
  display: flex;
  gap: 1rem;
  & li:hover {
    cursor: pointer;
  }
}
</style>
