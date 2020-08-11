<template>
  <c-flex
    p="50px"
    h="400px"
    bg="khaki"
    color="white"
    justify-content="center"
    align-items="center"
  >
    <c-heading as="h1" size="xl">TODO PRODUCT FEEDBACK SECTION</c-heading>
  </c-flex>
</template>

<script lang="js">
import {
  CFlex,
  CHeading
} from "@chakra-ui/vue"

export default {
  name: "ProductFeedback",
  components: {
    CFlex,
    CHeading
  }
}
</script>
