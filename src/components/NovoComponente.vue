<script>
export default {
  props: {
    titulo: {
      default: "A DEFINIR",
    },
    nomes: Array,
  },
};
</script>
<template>
  <main class="block">
    <h1>{{ titulo }}</h1>
    <ul>
      <li v-for="(nome, i) of nomes" :key="i">
        {{ nome }}
      </li>
    </ul>
  </main>
</template>
<style></style>
