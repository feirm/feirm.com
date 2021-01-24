<template>
  <nav
    class="navbar is-spaced is-dark"
    role="navigation"
    aria-label="main navigation"
  >
    <div class="container">
      <div class="navbar-brand">
        <nuxt-link to="/" class="branding"></nuxt-link>
        <a
          role="button"
          class="navbar-burger"
          id="burger"
          aria-label="menu"
          aria-expanded="false"
          data-target="nav-menu"
        >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>

      <div class="navbar-menu" id="nav-menu">
        <div class="navbar-end">
          <nuxt-link to="/platform" class="navbar-item has-text-weight-light">Platform</nuxt-link>
          <nuxt-link to="/blockchain" class="navbar-item has-text-weight-light">Blockchain</nuxt-link>
          <nuxt-link to="/kayda" class="navbar-item has-text-weight-light">Kayda</nuxt-link>
          <nuxt-link to="/downloads" class="navbar-item has-text-weight-light">Downloads</nuxt-link>
          <a href="https://docs.feirm.com" target="_blank" class="navbar-item has-text-weight-light">Documentation</a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
if (process.client) {
  const burger = document.getElementById('burger');
  const navbarMenu = document.getElementById('nav-menu');

  burger.addEventListener('click', () => {
    navbarMenu.classList.toggle('is-active');
  });
}
</script>

<style scoped>
/* Navigation Bar Branding */
.branding {
    background: url("../assets/logos/navbar.png") no-repeat center center;
    background-size: cover;
    width: 152px
}
</style>