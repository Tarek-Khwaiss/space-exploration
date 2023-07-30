<template>
  <HomeView></HomeView>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HomeView from "./views/HomeView.vue";

export default defineComponent({
  components: {
    HomeView,
  },
});
</script>

<style lang="scss">
#app {
  // height: 100%;
  // width: 100%;
}
</style>
