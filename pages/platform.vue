<template>
  <div>
    <!-- Landing hero -->
    <div class="hero is-dark has-orange-border-bottom">
      <div class="hero-body">
        <div class="container has-text-weight-light">
          <div class="columns is-centered is-vcentered">
            <div class="column is-4 is-offset-1">
              <img
                src="@/assets/platform/marketplace-wallet-combined.png"
                width="400px"
              />
            </div>
            <div class="column is-4">
              <h2 class="subtitle has-text-weight-light">
                Introducing the
                <span class="has-text-warning">Feirm Platform</span>.
              </h2>
              <h1 class="title is-1 has-text-weight-light">
                Secure.
                <br />
                Private.
                <br />
                Non-custodial.
              </h1>
              <a href="https://app.feirm.com" class="button is-warning"
                >Visit the Feirm Platform</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- History/background hero -->
    <div class="hero">
      <div class="hero-body">
        <div class="container">
          <div class="columns is-centered is-vcentered">
            <div class="column is-5 has-text-weight-light">
              <h1 class="title is-2 has-text-weight-light">
                It is time for a change.
              </h1>

              <div class="content">
                <p>
                  In 2020, there were 5 major hacks which took place on
                  cryptocurrency platforms/exchanges. The total value of these
                  hacks summed up to <strong>$286,933,760</strong>.
                </p>

                <p>
                  Alongside the initial theft of funds,
                  <strong>200 pieces</strong> of personally-identifiable
                  information were breached.
                </p>

                <p>
                  <span class="has-text-warning">Feirm</span> is here to solve
                  this problem by providing a secure, private and non-custodial
                  cryptocurrency platform for everyone.
                </p>
              </div>
            </div>

            <div class="column is-2 is-offset-1">
              <img src="@/assets/platform/money-bag.png" />
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- How is the Feirm platform different -->
    <div class="hero has-background-white-bis">
      <div class="hero-body">
        <div class="container">
          <h1 class="title has-text-weight-light has-text-centered">
            What do we have to offer?
          </h1>
          <div class="columns is-centered is-multiline">
            <!-- Differences/features -->
            <div class="column is-3 has-text-weight-light">
              <!-- Show some boxes with features -->
              <div class="box non-custodial">
                <h2 class="subtitle has-text-centered">Non-custodial</h2>
                <p>
                  We do not have access to our users cryptocurrency wallets, nor
                  do we store any cryptocurrency on behalf of our users. Your
                  funds are truly yours!
                </p>
              </div>
            </div>

            <div class="column is-3 has-text-weight-light">
              <div class="box non-custodial">
                <h2 class="subtitle has-text-centered">
                  State-of-the-art encryption
                </h2>
                <p>
                  End-to-end encryption is used to keep your Feirm account
                  secure. We do not store your password or any sensitive
                  information about you. It is encrypted before it even leaves
                  your device!
                </p>
              </div>
            </div>

            <div class="column is-3 has-text-weight-light">
              <!-- Show some boxes with features -->
              <div class="box non-custodial">
                <h2 class="subtitle has-text-centered">
                  Made with privacy in mind
                </h2>
                <p>
                  Feirm does not want to know anything about our users. We only
                  require a unique username, password and PIN to create an
                  account. All of your sensitive information is encrypted and
                  accessible by you, and only you.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Show app features -->
    <div class="hero">
      <div class="hero-body">
        <div class="container">
          <div class="columns is-centered is-vcentered">
            <div class="column is-5 has-text-weight-light">
              <h1 class="title is-2 has-text-weight-light">
                Send and receive with ease.
              </h1>

              <div class="content">
                <p>
                  <span class="has-text-warning">Feirm</span> makes it easy for
                  you to use your cryptocurrency. Send and receive your funds in
                  real-time. No delays when it comes to sending or receiving.
                  Everything happens instantly.
                </p>
              </div>
            </div>

            <div class="column is-2 is-offset-1">
              <img
                src="@/assets/platform/receive.gif"
                style="box-shadow: 0 0 20px rgba(0, 0, 0, 0.3)"
              />
            </div>
          </div>

          <br>
          <br>

          <div class="columns is-centered is-vcentered">
            <div class="column is-2">
              <img
                src="@/assets/platform/contact.png"
                style="box-shadow: 0 0 20px rgba(0, 0, 0, 0.3)"
              />
            </div>

            <div class="column is-5 has-text-weight-light is-offset-1">
              <h1 class="title is-2 has-text-weight-light">
                Zero-knowledge contacts.
              </h1>

              <div class="content">
                <p>
                  Store your Feirm contacts securely with zero-knowledge encryption. All contact data you provide is encrypted using your Feirm encryption key. We cannot access or modify the information you store for any of your contacts.
                </p>
              </div>
            </div>
          </div>

          <br>
          <br>

          <div class="columns is-centered is-vcentered">
            <div class="column is-5 has-text-weight-light">
              <h1 class="title is-2 has-text-weight-light">
                Peer-to-peer marketplace.
              </h1>
              <span class="tag is-dark">Coming Soon</span>
              <br>
              <br>
              <div class="content">
                <p>
                  Buy or sell items privately and securely on the <span class="has-text-warning">Feirm Marketplace</span>. Transact instantly with cryptocurrency. No need to wait days for a settlement as all transactions are handled by the blockchain. All communication between users are End-to-End Encrypted (E2EE), using trusted concepts developed by Signal and other secure messengers.
                </p>
              </div>
            </div>

            <div class="column is-2 is-offset-1">
              <img
                src="@/assets/platform/marketplace.png"
              />
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- List assets -->
  </div>
</template>

<style scoped>
/* Equal box height */
.box {
  height: 100%;
}
</style>