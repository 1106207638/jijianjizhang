<template>
  <button class="button"><slot /></button>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({});
</script>

<style lang="scss" scoped>
.button {
  background: #767676;
  color: white;
  border-radius: 4px;
  border: none;
  padding: 10px 16px;
  &-wrapper {
    text-align: center;
    padding: 16px;
    margin-top: 44-16px;
  }
}
</style>
