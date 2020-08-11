<template>
  <c-flex
    p="50px"
    h="150px"
    bg="tomato"
    color="white"
    justify-content="center"
    align-items="center"
  >
    <c-heading as="h1" size="xl">TODO FOOTER SECTION</c-heading>
  </c-flex>
</template>

<script lang="js">
import {
  CFlex,
  CHeading
} from "@chakra-ui/vue"

export default {
  name: "Footer",
  components: {
    CFlex,
    CHeading
  }
}
</script>
