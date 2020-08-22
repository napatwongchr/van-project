<template>
  <c-flex
    p="20px"
    bg="#4287f5"
    color="white"
    justify-content="space-between"
    align-items="center"
    h="80px"
  >
    <c-heading as="h1" size="lg">WJ Transport</c-heading>
    <c-stack is-inline spacing="5" align-items="center">
      <c-pseudo-box
        font-size="xl"
        pb="3px"
        cursor="pointer"
        :_hover="{ borderBottom: '3px solid white' }"
        >เกี่ยวกับเรา</c-pseudo-box
      >
      <c-pseudo-box
        font-size="xl"
        pb="3px"
        cursor="pointer"
        :_hover="{ borderBottom: '3px solid white' }"
        >ติดต่อเรา</c-pseudo-box
      >
    </c-stack>
  </c-flex>
</template>

<style scoped>
* {
  font-family: "kanit";
}
</style>

<script lang="js">
import {
  CHeading,
  CFlex,
  CPseudoBox,
  CStack
} from "@chakra-ui/vue"

export default {
  name: "Navbar",
  components: {
    CHeading,
    CFlex,
    CStack,
    CPseudoBox
  }
}
</script>
