<script setup>
import Forms from "@/components/Forms.vue";
import Signature from "@/components/Signature.vue";
</script>

<template>
  <div class="Main-container">
    <Signature Id="PD05" Signature="Thomas Rietz" Grade="Officer III"></Signature>
    <Forms></Forms>
  </div>
</template>

<style scoped>

.Main-container {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 50%;
  height: 50%;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
