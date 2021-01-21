<template>
  <div>
    <!-- Navigation component -->
    <Navigation />

    <!-- Main content -->
    <nuxt />
  </div>
</template>

<script>
import Navigation from "@/components/Navigation";

export default {
  components: {
    Navigation
  }
}
</script>
