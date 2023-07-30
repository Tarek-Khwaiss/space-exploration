<template>
  <div class="navigation-container">
    <img class="main-logo" src="../assets/shared/logo.svg" />
    <div class="horizontal-divider"></div>
    <div class="navigation-list"></div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  data() {
    return {
      home: "",
      destinations: "",
      crew: "",
      technology: "",
    };
  },
});
</script>

<style lang="scss" scoped>
.navigation-container {
  height: 5.5rem;
  opacity: 1;

  margin-top: 2rem;
  /* Add the blur effect */

  display: flex;

  .navigation-list {
    backdrop-filter: blur(20px);
    background: rgba(255, 255, 255, 0.07);
    height: 100%;
    width: 50%;
    justify-self: end;
  }
}
</style>
