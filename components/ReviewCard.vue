<template>
  <c-flex
    p="20px"
    w="400px"
    mx="50px"
    border-radius="20px"
    flex-direction="column"
  >
    <c-box
      w="35px"
      h="35px"
      border-radius="100%"
      justify-content="center"
      align-items="center"
      text-align="center"
      >I</c-box
    >
    <c-text>
      แอบมองดูฟ้าที่ฉันนั้นเห็นอยู่ในเวลาที่มีผู้คนหลากหลายปีกแห่งความฝัน
      ก็เหมือนเธอยิ่งไกลห่างไปให้เธอจะมุ่งไปด้วยกัน
      พวกเราพร้อมข้ามมันเปลี่ยนไปข้างในใจไม่ได้ดังใจเลือนลาง
      ความฝันเริ่มจากหยาดเหงื่อและน้ำตาเหมือนมีใครบันดาลให้มันไว้
      แค่ไหนเพียงใดก็ไม่เคยจะเดินผ่านแล้ว จะเป็นจะสักวันที่มีให้ใช้มา
      ไปในใจอยู่ตรงนี้ไม่เปลี่ยนไป ไม่ว่าใครสุดท้ายต้องมีเรื่องราวหมองหม่น
    </c-text>
  </c-flex>
</template>

<style scoped>
* {
  font-family: "kanit";
}
</style>

<script lang="js">
import {
  CText,
  CFlex,
} from "@chakra-ui/vue"

export default {
  name: "ReviewCard",
  components: {
    CText,
    CFlex,
  },
}
</script>
