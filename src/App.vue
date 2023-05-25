<script>
import HeaderDiv from "./components/HeaderDiv.vue";
import NominateDiv from "./components/NominateDiv.vue";
import FooterDiv from "./components/FooterDiv.vue";

export default {
  name: "App",
  components: {
    HeaderDiv,
    NominateDiv,
    FooterDiv,
  },
};
</script>

<template>
  <div id="app">
    <HeaderDiv />

    <NominateDiv />

    <FooterDiv />
  </div>
</template>

<style></style>

<!-- 
<script setup lang="ts">
import HeaderDiv from "./components/HeaderDiv.vue";
import NominateDiv from "./components/NominateDiv.vue";
import FooterDiv from "./components/FooterDiv.vue";
</script>

<template>
  <HeaderDiv />

  <NominateDiv />

  <FooterDiv />
</template>

<style></style> -->
