<template>
  <div h="100%">
    <Navbar />
    <FeatureSection />
  </div>
</template>

<script lang="js">
import Navbar from "../components/Navbar"
import FeatureSection from "../components/FeatureSection"

export default {
  name: "Home",
  components: {
    Navbar,
    FeatureSection
  }
}
</script>
