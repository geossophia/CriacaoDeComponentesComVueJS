<script>
import MenuLateral from "@/components/MenuLateral.vue";
import CabecalhoCima from "@/components/CabecalhoCima.vue";
import PrincipalContent from "@/components/PrincipalContent.vue";
import FooterRodape from "@/components/FooterRodape.vue";
export default {
  components: {
    MenuLateral,
    CabecalhoCima,
    PrincipalContent,
    FooterRodape,
  },
};
</script>
<template>
  <MenuLateral />
  <CabecalhoCima />
  <PrincipalContent />
  <FooterRodape />
</template>
<style></style>
