<template>
  <c-flex p="25px 50px 50px 50px" color="#4287f5" flex-direction="column">
    <c-heading as="h1" size="xl" my="20px" text-align="center"
      >บริการของเรา</c-heading
    >
    <c-flex
      :flex-direction="['column', 'row', 'row', 'row']"
      justify-content="center"
      align-items="center"
    >
      <service-card
        :icon-url="require('../assets/icons/safty-first.svg')"
        content-text="ปลอดภัยมาก่อน"
      ></service-card>
      <service-card
        :icon-url="require('../assets/icons/good-van.svg')"
        content-text="รถดีมีคุณภาพ"
      ></service-card>
      <service-card
        :icon-url="require('../assets/icons/good-driver.svg')"
        content-text="ขับโดยผู้ขับมืออาชีพ"
      ></service-card>
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

import ServiceCard from "../components/ServiceCard"

export default {
  name: "ProductFeature",
  components: {
    CFlex,
    CHeading,
    ServiceCard
  }
}
</script>
