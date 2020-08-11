<template>
  <c-flex p="20px" bg="tomato" color="white" justify-content="space-between">
    <h1>Van LOGO test</h1>
    <c-stack is-inline spacing="5">
      <c-flex>About Us</c-flex>
      <c-flex>Contact Us</c-flex>
    </c-stack>
  </c-flex>
</template>

<script lang="js">
import {
  CFlex,
  CStack
} from "@chakra-ui/vue"

export default {
  name: "Navbar",
  components: {
    CFlex,
    CStack
  }
}
</script>
