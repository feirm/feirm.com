<template>
  <div>
    <div class="hero is-medium is-dark has-orange-border-bottom">
      <div class="hero-body">
        <div class="container has-text-centered has-text-weight-light">
          <h1 class="title is-1 has-text-weight-light">
            The backbone of decentralisation.
          </h1>
          <p>
            The <span class="has-text-warning">Feirm</span> project maintains a
            blockchain which is vital for components of the ecosystem to
            function.
          </p>
          <br />
          <a
            href="https://github.com/feirm/feirm"
            target="_blank"
            class="button is-warning has-text-centered"
            >Visit our GitHub</a
          >
        </div>
      </div>
    </div>

    <!-- Features -->
    <div class="hero has-background-white-bis">
      <div class="hero-body">
        <div class="container has-text-weight-light">
          <h1 class="title has-text-weight-light has-text-centered">
            Why use the <span class="has-text-warning">Feirm</span> blockchain?
          </h1>
          <div class="columns is-centered">
            <!-- Sustainable -->
            <div class="column is-3">
              <div class="box has-text-centered">
                <span class="icon is-large">
                  <font-awesome-icon :icon="['fas', 'leaf']" />
                </span>
                <h2 class="subtitle">Sustainability</h2>
                <p class="has-text-left">
                  At its core, the
                  <span class="has-text-warning">Feirm</span> blockchain is a
                  low energy alternative to Proof of Work blockchains due to
                  Proof of Stake consensus being used.
                </p>
              </div>
            </div>

            <!-- Decentralised -->
            <div class="column is-3">
              <div class="box has-text-centered">
                <span class="icon is-large">
                  <font-awesome-icon :icon="['fas', 'cubes']" />
                </span>
                <h2 class="subtitle">Decentralised</h2>
                <p class="has-text-left">
                  Due to the nature of blockchains, no single entity controls
                  the <span class="has-text-warning">Feirm</span> network. The
                  network is made up from hundreds of nodes scattered across the
                  globe.
                </p>
              </div>
            </div>

            <!-- Private -->
            <div class="column is-3">
              <div class="box has-text-centered">
                <span class="icon is-large">
                  <font-awesome-icon :icon="['fas', 'eye-slash']" />
                </span>
                <h2 class="subtitle">Private</h2>
                <p class="has-text-left">
                  No accounts are required to transact on the
                  <span class="has-text-warning">Feirm</span> blockchain. All
                  you need to get started receiving funds is a Feirm
                  cryptocurrency address - which are not related to your
                  identity.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Coin overview -->
    <div class="hero">
      <div class="hero-body">
        <div class="container has-text-weight-light">
          <h1 class="title has-text-weight-light has-text-centered">
            Coin Overview
          </h1>
          <div class="columns is-centered is-multiline">
            <!-- Launch date -->
            <div class="column is-3">
              <div class="box has-text-centered">
                <span class="icon is-large">
                  <font-awesome-icon :icon="['fas', 'seedling']" />
                </span>
                <h2 class="subtitle">Launch Date</h2>
                <p class="has-text-left">
                  The <span class="has-text-warning">Feirm</span> genesis block
                  was created on the <b>22nd February 2018</b>, ultimately
                  bringing our blockchain to life.
                </p>
              </div>
            </div>

            <!-- Block time -->
            <div class="column is-3">
              <div class="box has-text-centered">
                <span class="icon is-large">
                  <font-awesome-icon :icon="['fas', 'clock']" />
                </span>
                <h2 class="subtitle">Block Time</h2>
                <p class="has-text-left">
                  The average block time for the network is <b>2 minutes</b>.
                  This is <b>5x faster</b> than the Bitcoin network.
                </p>
              </div>
            </div>

            <!-- Consensus -->
            <div class="column is-3">
              <div class="box has-text-centered">
                <span class="icon is-large">
                  <font-awesome-icon :icon="['fas', 'coins']" />
                </span>
                <h2 class="subtitle">Consensus Mechanism</h2>
                <p class="has-text-left">
                  The <span class="has-text-warning">Feirm</span> blockchain
                  uses the Proof of Stake consensus mechanism along with
                  Masternodes for governence.
                </p>
              </div>
            </div>

            <!-- Max supply -->
            <div class="column is-3">
              <div class="box has-text-centered">
                <span class="icon is-large">
                  <font-awesome-icon :icon="['fas', 'chart-line']" />
                </span>
                <h2 class="subtitle">Maximum Supply</h2>
                <p class="has-text-left">
                  A maximum of <b>100,000,000</b>
                  <span class="has-text-warning">XFE</span> can ever be minted
                  on the <span class="has-text-warning">Feirm</span> blockchain,
                  eventually causing it to become a rare asset.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Resources -->
    <div class="hero has-background-white-bis">
      <div class="hero-body">
        <div class="container has-text-centered has-text-weight-light">
          <h1 class="title has-text-weight-light">Resources</h1>
          <div class="columns is-centered">
            <div class="column is-4">
              <p>
                In order for you to get familiar with the
                <span class="has-text-warning">Feirm</span> blockchain, please
                checkout the following resources.
              </p>
            </div>
          </div>

          <div class="columns is-centered">
            <div class="column is-3">
              <div class="box">
                <span class="icon is-large">
                  <font-awesome-icon :icon="['fas', 'wallet']" />
                </span>
                <h2 class="subtitle">Desktop Wallets</h2>
                <p class="has-text-left">
                  The <span class="has-text-warning">Feirm</span> project
                  provides QT desktop wallets for Windows, MacOS and Linux. You
                  can stake and store your cryptocurrency in this wallet.
                </p>
                <br />
                <a
                  href="https://github.com/feirm/feirm/releases/latest"
                  target="_blank"
                  class="button is-warning is-fullwidth"
                  >Download latest wallet</a
                >
              </div>
            </div>

            <div class="column is-3">
              <div class="box">
                <span class="icon is-large">
                  <font-awesome-icon :icon="['fas', 'globe-europe']" />
                </span>
                <h2 class="subtitle">Feirm Platform</h2>
                <p class="has-text-left">
                  If you wish to store and transact in the
                  <span class="has-text-warning">Feirm (XFE)</span>
                  cryptocurrency as well as other assets, you can create a
                  non-custodial wallet on the Feirm Platform.
                </p>
                <br />
                <a
                  href="https://app.feirm.com"
                  target="_blank"
                  class="button is-warning is-fullwidth"
                  >Visit the Feirm Platform</a
                >
              </div>
            </div>

            <div class="column is-3">
              <div class="box">
                <span class="icon is-large">
                  <font-awesome-icon :icon="['fas', 'box']" />
                </span>
                <h2 class="subtitle">Blockchain Bootstrap</h2>
                <p class="has-text-left">
                  Get your <span class="has-text-warning">Feirm</span> desktop
                  wallet synced as fast as possible by downloading a copy of the
                  blockchain from our Bootstrap platform.
                </p>
                <br />
                <a
                  href="https://app.feirm.com"
                  target="_blank"
                  class="button is-warning is-fullwidth"
                  >Download a bootstrap</a
                >
              </div>
            </div>

            <div class="column is-3">
              <div class="box">
                <span class="icon is-large">
                  <font-awesome-icon :icon="['fas', 'search']" />
                </span>
                <h2 class="subtitle">Explorer</h2>
                <p class="has-text-left">
                  Have an address or transaction that you want to lookup? Find
                  all the information you need about the blockchain at our
                  Blockchain Explorer.
                </p>
                <br />
                <a
                  href="https://blockbook.feirm.com"
                  target="_blank"
                  class="button is-warning is-fullwidth"
                  >Visit the Blockchain Explorer</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Buy Feirm cryptocurrency -->
    <div class="hero">
      <div class="hero-body">
        <div class="container has-text-centered has-text-weight-light">
          <h1 class="title has-text-weight-light">
            Where can I buy <span class="has-text-warning">Feirm (XFE)</span>?
          </h1>
          <p>
            The <span class="has-text-warning">XFE</span> cryptocurrency can be
            purchased through the following exchanges/methods.
          </p>
          <div class="columns is-centered">
            <div class="column is-3">
              <div class="box">
                <figure class="image is-3by1">
                  <img src="@/assets/logos/birake.png" />
                </figure>

                <h2 class="subtitle">Birake Exchange</h2>
                <p>
                  Birake is decentralised exchange. It is a regulated however,
                  making it subject to KYC/AML.
                </p>
                <br />
                <a
                  href="https://trade.birake.com/market/BIRAKE.XFE_BIRAKE.BTC"
                  target="_blank"
                  class="button is-warning is-fullwidth"
                  >XFE/BTC Market Pair</a
                >
              </div>
            </div>

            <div class="column is-3">
              <div class="box">
                <figure class="image is-3by1">
                  <img src="@/assets/logos/discord.png" />
                </figure>

                <h2 class="subtitle">Discord Bot</h2>
                <p>
                  Purchase
                  <span class="has-text-warning">XFE</span> over-the-counter
                  (OTC) in our Discord Server. This bot is <b>not</b> maintained
                  or created by Feirm.
                </p>
                <br />
                <a
                  href="https://discord.gg/mUZdSKg"
                  target="_blank"
                  class="button is-warning is-fullwidth"
                  >Visit our Discord server</a
                >
              </div>
            </div>

            <div class="column is-3">
              <div class="box">
                <figure class="image is-64x64" style="margin: 0 auto; margin-bottom: 29px">
                  <img src="@/assets/logos/feirm.png" />
                </figure>

                <h2 class="subtitle">Feirm Platform</h2>
                <p>
                  Soon, you will be able to purchase cryptocurrency through the <span class="has-text-warning">Feirm</span> platform in a trustless and secure way.
                </p>
                <br />
                <a
                  class="button is-dark is-fullwidth disabled"
                  >Coming Soon</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* Large icon */
.is-large {
  font-size: 64px;
}

/* Equal box height */
.box {
  height: 100%;
}
</style>