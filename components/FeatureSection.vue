<template>
  <c-flex
    p="50px"
    h="350px"
    bg="lightgrey"
    color="white"
    justify-content="center"
    align-items="center"
  >
    <c-heading as="h1" size="xl">TODO FEATURE SECTION</c-heading>
  </c-flex>
</template>

<script lang="js">
import {
  CFlex,
  CHeading
} from "@chakra-ui/vue"

export default {
  name: "FeatureSection",
  components: {
    CFlex,
    CHeading
  }
}
</script>
