<template>
  <c-flex
    p="50px"
    h="500px"
    bg="#4287f5"
    color="white"
    flex-direction="column"
    justify-content="center"
    align-items="center"
    font-family="kanit"
  >
    <c-heading as="h1" size="2xl">บริการรถตู้พร้อมคนขับมืออาชีพ</c-heading>
    <c-text mt="20px" font-size="2xl">
      รับ-ส่งสนามบิน, ท่องเที่ยวทั่วประเทศไทย, รับเหมาออกต่างจังหวัด,
      และต่อวีซ่า รับส่งด่าน ตม.
    </c-text>
    <c-text mt="20px" font-size="2xl">
      มีรถหลากหลายประเภท รถตู้แบบ VIP 9 ที่นั่ง, 10 ที่นั่ง และ 13 ที่นั่ง
    </c-text>
    <c-button
      mt="30px"
      size="lg"
      bg="white"
      color="#4287f5"
      font-size="2xl"
      @click="log()"
      >เรียกรถตู้ติดต่อ 065-5133399</c-button
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
  CButton,
  CText,
  CFlex,
  CHeading
} from "@chakra-ui/vue"

export default {
  name: "FeatureSection",
  components: {
    CButton,
    CText,
    CFlex,
    CHeading
  },
  methods: {
    log() {
      console.log('link to line')
    }
  }
}
</script>
