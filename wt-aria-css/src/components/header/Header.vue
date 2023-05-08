<template>
  <div class="header">
    <li  class="logo">Developer</li>
    <nav aria-label="Main Navigation">
      <ul>
        <li><a href="#">About</a></li>
        <li class="dropdown">
          <!-- aria-expanded needs managed with Javascript -->
          <button
              type="button"
              class="dropdown__title"
              aria-expanded="false"
              aria-controls="sweets-dropdown"
          >
            Service
          </button>
          <ul class="dropdown__menu" id="sweets-dropdown">
            <li>Webdevelopment</li>
            <li>Networking</li>
            <li>SocialMedia</li>
            <li>SEO</li>
          </ul>
        </li>
        <li><a href="#">Order</a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
@import "./header.css";
</style>