<template>
  <div class="Nav-wrapper">
    <div class="content">
      money.vue
    </div>
    <Nav />
  </div>
</template>

<script>
export default {
  name: "Money",
};
</script>

<style lang="scss" scoped>
.Nav-wrapper {
  border: 1px solid green;
  display: flex;
  flex-direction: column;
  height: 100vh;
}
.content {
  flex-grow: 1;
  overflow: auto;
}
</style>
