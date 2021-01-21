<template>
  <div>
    <!-- Banner component -->
    <Banner />

    <!-- Navigation component -->
    <Navigation />

    <!-- Main content -->
    <nuxt />
  </div>
</template>

<script>
import Banner from "@/components/Banner";
import Navigation from "@/components/Navigation";

export default {
  components: {
    Banner,
    Navigation
  }
}
</script>
