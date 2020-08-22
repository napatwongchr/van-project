<template>
  <c-flex p="25px 50px 50px 50px" color="#4287f5" flex-direction="column">
    <c-heading as="h1" size="xl" my="20px" text-align="center"
      >ภาพบรรยากาศใช้งานจริง</c-heading
    >
    <c-stack is-inline justify-content="center" spacing="10" mt="20px">
      <c-flex>
        <img src="https://picsum.photos/400/300"></img>
      </c-flex>
       <c-flex>
        <img src="https://picsum.photos/400/300"></img>
      </c-flex>
       <c-flex>
        <img src="https://picsum.photos/400/300"></img>
      </c-flex>
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
  CFlex,
  CStack,
  CHeading
} from "@chakra-ui/vue"

export default {
  name: "ImageFeature",
  components: {
    CFlex,
    CStack,
    CHeading
  }
}
</script>
