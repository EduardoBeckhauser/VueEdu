<script>
import MenuLateral from "@/components/MenuLateral.vue";
import MenuConteudo from "@/components/MenuConteudo.vue";
import CabePrincipal from "@/components/CabePrincipal.vue";
import RodaPrincipal from "@/components/RodaPrincipal.vue";

export default {
  components: { MenuLateral, MenuConteudo, CabePrincipal, RodaPrincipal },
};
</script>
<template>
  <MenuLateral />
  <CabePrincipal />
  <MenuConteudo />
  <RodaPrincipal />
</template>
<style></style>
