<template>
  <div>
    <div class="hero is-dark has-orange-border-bottom">
      <div class="hero-body">
        <div class="container medium">
          <div class="columns is-vcentered is-centered">
            <div class="column is-5 has-text-left has-text-centered-mobile">
              <h1 class="title is-1 has-text-weight-light">
                Privacy for everyone.
              </h1>
              <p class="subtitle has-text-weight-light">
                Feirm is a blockchain project that is building a secure platform
                which is easy to use and private by design.
              </p>
              <div
                class="buttons is-left is-centered-mobile has-text-weight-light"
              >
                <a
                  target="_blank"
                  href="https://app.feirm.com"
                  class="button is-warning is-medium"
                  >Get the Feirm app</a
                >
              </div>
            </div>
            <div class="column is-2 has-text-centered-mobile">
              <img src="@/assets/wallet/overview.png" width="250px" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomePage",
};
</script>
