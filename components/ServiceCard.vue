<template>
  <c-flex
    p="20px"
    w="400px"
    mx="70px"
    border-radius="20px"
    flex-direction="column"
    align-items="center"
  >
    <img
      id="svg-icon"
      :src="iconUrl"
      :width="['60px', '60px', '100px', '100px']"
      :height="['60px', '60px', '100px', '100px']"
    />
    <c-text mt="50px" font-size="30px">
      {{ contentText }}
    </c-text>
  </c-flex>
</template>

<style scoped>
* {
  font-family: "kanit";
}

#svg-icon {
  fill: "red";
}
</style>

<script lang="js">
import {
  CText,
  CFlex,
} from "@chakra-ui/vue"

export default {
  name: "ServiceCard",
  components: {
    CText,
    CFlex,
  },
  props: ['iconUrl', 'contentText'],
}
</script>
