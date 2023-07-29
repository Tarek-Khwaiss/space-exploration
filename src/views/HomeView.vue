<template>
  <h1>{{ heading1 }}</h1>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  data() {
    return {
      heading1: "test",
    };
  },
});
</script>

<style lang="scss" scoped></style>
