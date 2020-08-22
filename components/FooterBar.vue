<template>
  <c-flex p="10px" h="40px" justify-content="center" align-items="center">
    <c-text size="md" color="#4287f5"
      >© 2020 WJ Transport All rights reserved.</c-text
    >
  </c-flex>
</template>

<style scoped>
* {
  font-family: "kanit";
}
</style>

<script lang="js">
import {
  CFlex,
  CText
} from "@chakra-ui/vue"

export default {
  name: "Footer",
  components: {
    CFlex,
    CText
  }
}
</script>
