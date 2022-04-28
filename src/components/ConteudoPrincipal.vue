<script>
import NovoComponente from "./NovoComponente.vue";
export default {
  components: {
    NovoComponente,
  },
  data() {
    return {
      professores: ["Eduardo, Marco, Ivo"],
    };
  },
};
</script>
<template>
  <main id="content">
    <NovoComponente titulo="Alunos" :nomes="['Jeniffer', 'Isa']" />
    <NovoComponente titulo="Professores" :nomes="professores" />
    <NovoComponente class="alerta" />
    <NovoComponente class="alerta" />
    <NovoComponente />
    <NovoComponente />
  </main>
</template>
<style></style>
