<script>
import MenuLateral from "@/components/MenuLateral.vue";
import ConteudoPrincipal from "@/components/ConteudoPrincipal.vue";
import CabecalhoPrincipal from "@/components/CabecalhoPrincipal.vue";
import RodapePrincipal from "@/components/RodapePrincipal.vue";
export default {
  components: {
    MenuLateral,
    ConteudoPrincipal,
    CabecalhoPrincipal,
    RodapePrincipal,
  },
};
</script>
<template>
  <MenuLateral />
  <CabecalhoPrincipal />
  <ConteudoPrincipal />
  <RodapePrincipal />
  <footer id="footer">Rodapé</footer>
</template>
<style></style>
