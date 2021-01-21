<template>
  <nav
    class="navbar is-spaced is-dark"
    role="navigation"
    aria-label="main navigation"
  >
    <div class="container">
      <div class="navbar-brand">
        <a href="/" class="branding"></a>
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
          <a href="/wallet/" class="navbar-item has-text-weight-light"
            >Wallet</a
          >
          <a
            href="https://docs.feirm.com"
            class="navbar-item has-text-weight-light"
            >Documentation</a
          >
          <a href="/downloads/" class="navbar-item has-text-weight-light"
            >Downloads</a
          >
        </div>
      </div>
    </div>
  </nav>
</template>

<style scoped>
/* Navigation Bar Branding */
.branding {
    background: url("../assets/logos/navbar.png") no-repeat center center;
    background-size: cover;
    width: 152px
}
</style>