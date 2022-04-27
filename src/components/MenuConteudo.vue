<script>
import BlocoMeio from "@/components/BlocoMeio.vue";
export default {
  components: { BlocoMeio },
};
</script>
<template>
  <main id="content">
    <BlocoMeio titulo="Area 1" class="corum" :nomes="['Eduardo', 'Rosa']" />
    <BlocoMeio titulo="Area 2" class="cordois" :nomes="['Gustavo', 'Azul']" />
    <BlocoMeio titulo="Area 3" class="cortres" :nomes="['Rafaela', 'Verde']" />
    <BlocoMeio titulo="Area 4" class="corquatro" :nomes="['Heloisa', 'Roxo']" />
    <BlocoMeio titulo="Area 5" class="corcinco" :nomes="['Pedro', 'Amarelo']" />
    <BlocoMeio titulo="Area 6" class="corseis" :nomes="['Lucas', 'Vermelho']" />
  </main>
</template>
<style></style>
