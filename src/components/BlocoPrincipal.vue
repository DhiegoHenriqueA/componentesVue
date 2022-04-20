<script>
import Artigo from "./Artigo.vue";
export default {
  components: { Artigo },
};
</script>
<template>
  <main id="content">
    <Artigo class="box-artigo" />
    <Artigo class="box-artigo" />
    <Artigo class="box-artigo" />
    <Artigo class="box-artigo" />
    <Artigo class="box-artigo" />
    <Artigo class="box-artigo" />
  </main>
</template>
<style>
.box-artigo {
  background-color: grey;
}
</style>
