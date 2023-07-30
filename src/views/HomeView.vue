<template>
  <div class="background"></div>
  <Navigation></Navigation>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Navigation from "@/components/Navigation.vue";

export default defineComponent({
  components: {
    Navigation,
  },
  data() {
    return {
      heading1: "test",
    };
  },
});
</script>

<style lang="scss" scoped>
h1 {
  margin-top: 0;
  color: white;
}
.background {
  @include background("../assets/home/background-home-desktop.jpg");
}
</style>
