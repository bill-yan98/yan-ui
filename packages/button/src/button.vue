<template>
  <button class="y-btn">
    <span v-if="$slots.default"><slot></slot></span>
  </button>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "y-button",
});
</script>

<style scoped></style>
