<template>
  <div>
    <!-- Landing hero -->
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

    <!-- Distinct Feirm features -->
    <div class="hero">
      <div class="hero-body">
        <div class="container">
          <div class="columns is-centered is-vcentered">
            <div class="column is-5">
              <div class="box gradient-bg">
                <div class="content">
                  <h2 class="has-text-light has-text-weight-light">
                    The Feirm blockchain is a peer-to-peer network where you can
                    earn and use the native XFE currency.
                  </h2>
                  <a
                    target="_blank"
                    href="https://github.com/feirm/feirm"
                    class="button is-warning has-text-weight-light"
                  >
                    Learn More
                  </a>
                </div>
              </div>
            </div>
            <div class="column is-4 is-offset-1">
              <div class="content">
                <h2 class="subtitle has-text-weight-light">Global Network</h2>
                <p class="has-text-weight-light">
                  The Feirm network is made up from peers all over the world
                  allowing for no single point of failure. Transact without
                  disruption.
                </p>
                <h2 class="subtitle has-text-weight-light">
                  Developing Ecosystem
                </h2>
                <p class="has-text-weight-light">
                  The Feirm Ecosystem is constantly growing. Participate in our
                  network by operating a node and staking, or use the Feirm app
                  to interact with the network and other services.
                </p>
                <h2 class="subtitle has-text-weight-light">Censorship Free</h2>
                <p class="has-text-weight-light">
                  The Feirm network is available for everyone. Regardless of who
                  you are, or your geographical location - we have you covered!
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Show off some infrastructure -->
    <div class="hero has-background-light">
      <div class="hero-body">
        <div class="container">
          <div
            class="columns is-centered has-text-centered has-text-weight-light"
          >
            <!-- Blockchain Explorer -->
            <div class="column is-3">
              <div class="content">
                <span class="icon is-large">
                  <font-awesome-icon :icon="['fas', 'search']" />
                </span>

                <h2 class="subtitle has-text-weight-light">Block Explorer</h2>
                <p>Search for blocks, addresses and transactions.</p>
                <a
                  href="https://blockbook.feirm.com"
                  target="_blank"
                  class="button is-outlined is-warning"
                  >Visit Block Explorer</a
                >
              </div>
            </div>

            <!-- Progressive Web App -->
            <div class="column is-3">
              <div class="content">
                <span class="icon is-large">
                  <font-awesome-icon :icon="['fas', 'mobile-alt']" />
                </span>

                <h2 class="subtitle has-text-weight-light">Feirm App</h2>
                <p>Feirm Platform - Progressive Web Application (PWA)</p>
                <a
                  href="https://app.feirm.com"
                  target="_blank"
                  class="button is-outlined is-warning"
                  >Open the Feirm App</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Privacy features -->
    <div class="hero">
      <div class="hero-body">
        <div class="container">
          <h1 class="title is-2 has-text-weight-light has-text-centered">
            Private and Secure by Design
          </h1>
          <div class="columns is-centered">
            <div class="column is-4 has-text-weight-light">
              <div class="content">
                <h2 class="subtitle has-text-weight-light">Anonymity</h2>
                <p class="has-text-weight-light">
                  Getting started with the Feirm Ecosystem doesn't require any
                  personally-identifiable information. Feirm wallets are not
                  tied to your identity, and a Feirm account only requires a
                  unique username and strong password. That's it!
                </p>
                <h2 class="subtitle has-text-weight-light">
                  No ads or trackers
                </h2>
                <p class="has-text-weight-light">
                  The Feirm app contains zero ads or trackers. We aren't in the
                  business of tracking your every action throughout our app, nor
                  are we in the business of selling your data. We only collect
                  what we need to at the very minimum.
                </p>
                <h2 class="subtitle has-text-weight-light">Open source</h2>
                <p class="has-text-weight-light">
                  We ❤️ open source. We are committed to both using and writing
                  open source software. In fact, the majority of the products we
                  develop at Feirm is open source on GitHub!
                </p>
              </div>
            </div>
            <div class="column is-5 is-offset-1">
              <div class="content">
                <h2 class="subtitle has-text-weight-light">Encryption</h2>
                <p class="has-text-weight-light">
                  We take data security seriously. Feirm does not store
                  passwords (in the typical sense) or collect sensitive data in
                  plain-text form. Any sensitive data is encrypted on your
                  device before it is stored on our servers for safe-keeping.
                </p>
              </div>
              <br />
              <div class="box encryption-bg">
                <h2 class="subtitle has-text-weight-light has-text-light">
                  In June 2020, the Ledger hardware wallet company suffered a
                  data breach which exposed over 1 million email addresses and
                  20,000 home addresses.
                </h2>
                <h2 class="subtitle has-text-weight-light has-text-light">
                  As a result, individuals have been targeted through phishing
                  attempts, cold calls, and even physical threats against their
                  families.
                </h2>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Fetch recent posts from Medium -->
    <div class="hero has-background-light">
      <div class="hero-body">
        <div class="container has-text-centered has-text-weight-light">
          <h1 class="title is-2 has-text-weight-light">Latest Articles</h1>

          <!-- Iterate through the articles -->
          <div class="columns is-centered is-multiline">
            <div class="column is-3" v-for="article in articles" v-bind:key="article.title">
              <div class="card">
                <div class="card-image">
                  <figure class="image is-16by9">
                    <img :src="article.thumbnail" />
                  </figure>
                </div>
                <div class="card-content">
                  <div class="content">
                    <a :href="article.link" target="_blank">
                      <h4 class="has-text-weight-light has-text-dark">{{ article.title }}</h4>
                    </a>
                    <p class="help">{{ article.pubDate | formatDate }}</p>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Read all articles button -->
          <a href="https://medium.com/feirm" target="_blank" class="button is-medium is-warning">Read all articles</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Vue from "vue";
import moment from "moment";

export default Vue.extend({
  name: "Index",
  data() {
    return {
      articles: [],
    };
  },
  filters: {
    formatDate: function(time) {
      return moment(time).format('ll');
    }
  },
  methods: {
    async fetchArticles() {
      const MEDIUM_URL = "https://medium.com/feed/feirm";
      const RSS_JSON =
        "https://api.rss2json.com/v1/api.json?rss_url=" + MEDIUM_URL;

      const articles = await this.$axios.$get(RSS_JSON);
      this.articles = articles.items.splice(0, 3);
    },
  },
  async created() {
    this.fetchArticles();
  },
});
</script>

<style scoped>
/* Orange border */
.has-orange-border-bottom {
  border-bottom: 10px solid #f69738;
}

/* Box padding */
.box {
  padding: 3.75rem;
}

/* Gradient background with logo */
.gradient-bg {
  background-image: url("../assets/logos/card_transparent.png"),
    linear-gradient(#303030, #1c1c1c);
  background-repeat: no-repeat;
  background-position: bottom right;
}

/* Large icon */
.is-large {
  font-size: 64px;
}

/* Privacy and encryption features background */
.encryption-bg {
  background: linear-gradient(#303030, #1c1c1c);
}

/* Equal card height */
.card {
  height: 100%;
}
</style>