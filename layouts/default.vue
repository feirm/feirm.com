<template>
  <div>
    <!-- Banner component -->
    <Banner />

    <!-- Navigation component -->
    <Navigation />

    <!-- Main content -->
    <nuxt />

    <!-- Footer component -->
    <Footer />
  </div>
</template>

<script>
import Banner from "@/components/Banner";
import Navigation from "@/components/Navigation";
import Footer from "@/components/Footer";

export default {
  components: {
    Banner,
    Navigation,
    Footer
  }
}
</script>
