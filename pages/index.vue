<template>
  <div h="100%">
    <Navbar />
    <FeatureSection />
    <ProductFeature />
    <ProductFeedback />
    <Footer />
  </div>
</template>

<script lang="js">
import Navbar from "../components/Navbar"
import FeatureSection from "../components/FeatureSection"
import ProductFeature from "../components/ProductFeature"
import ProductFeedback from "../components/ProductFeedback"
import Footer from "../components/Footer"

export default {
  name: "Home",
  components: {
    Navbar,
    FeatureSection,
    ProductFeature,
    ProductFeedback,
    Footer
  }
}
</script>
