<script>
import MenuLateral from "@/components/MenuLateral.vue";
import Cabecalho from "./components/Cabecalho.vue";
import BlocoPrincipal from "./components/BlocoPrincipal.vue";
import Rodape from "./components/Rodape.vue";
export default {
  components: { MenuLateral, Cabecalho, BlocoPrincipal, Rodape },
};
</script>
<template>
  <MenuLateral />
  <Cabecalho />
  <BlocoPrincipal />
  <Rodape />
</template>
<style></style>
