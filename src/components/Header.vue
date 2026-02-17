<script setup></script>

<template>
  <div class="header container">
    <img
      src="https://res.cloudinary.com/lereacteur-apollo/image/upload/v1704448979/RNCP31114/cours-vue/exo-sem-1/my-blog-avatar_xhjc4e.png"
      alt="logo"
    />
    <H2>My blog</H2>
  </div>
  <div class="line"></div>
</template>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: var(--header-height);
  padding: 10px 0px;
  box-sizing: border-box;
}

.header img {
  height: calc(var(--header-height) - 20px);
}

.line {
  border-bottom: 4px solid var(--main-yellow);
}
</style>
