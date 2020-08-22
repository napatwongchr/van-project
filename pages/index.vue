<template>
  <div>
    <navbar />
    <feature-section />
    <product-feature />
    <image-feature />
    <product-review />
    <footer-bar />
  </div>
</template>

<script lang="js">
import Navbar from "../components/Navbar"
import FeatureSection from "../components/FeatureSection"
import ProductFeature from "../components/ProductFeature"
import ProductReview from "../components/ProductReview"
import ImageFeature from "../components/ImageFeature"
import FooterBar from "../components/FooterBar"

export default {
  name: "Home",
  components: {
    Navbar,
    FeatureSection,
    ProductFeature,
    ProductReview,
    FooterBar
  }
}
</script>
