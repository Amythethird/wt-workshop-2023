<template>
  <div class="header">
    <li  class="logo">Developer</li>
    <nav aria-label="Main Navigation">
      <ul>
        <li>Über mich</li>
        <li class="dropdown">
          <!-- aria-expanded needs managed with Javascript -->
          <div
              type="button"
              class="dropdown__title"
              aria-expanded="false"
              aria-controls="sweets-dropdown"
          >
            Services
          </div>
          <ul class="dropdown__menu" id="sweets-dropdown">
            <li>Webdevelopment</li>
            <li>Networking</li>
            <li>SocialMedia</li>
            <li>SEO</li>
          </ul>
        </li>
        <li>Kontakt</li>
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