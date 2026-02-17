<script setup></script>

<template>
  <div class="line"></div>

  <div class="footer container">
    <p>
      Made with <span>Vue.js</span> by
      <a href="https://github.com/MarionA34" target="_blank">Marion Abadie Aoun</a>
    </p>
  </div>
</template>

<style scoped>
.footer {
  height: var(--footer-height);
  display: flex;
  justify-content: center;
  align-items: center;
}

.line {
  border-top: 4px solid var(--main-yellow);
}

span,
a {
  color: var(--main-yellow);
  font-weight: bold;
}

a {
  text-decoration: none;
}
</style>
