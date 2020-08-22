<template>
  <c-flex p="25px 50px 50px 50px" color="#4287f5" flex-direction="column">
    <c-heading as="h1" size="xl" my="20px" text-align="center"
      >รีวิวจากผู้ใช้งาน</c-heading
    >
    <c-flex justify-content="center" align-items="center">
      <c-text color="lightgrey">ยังไม่มีรีวิวขณะนี้</c-text>
    </c-flex>
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
