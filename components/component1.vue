<template>
  <div class="component1-container"></div>
</template>

<script>
export default {
  name: 'Component1',
  props: {},
}
</script>

<style scoped>
.component1-container {
  width: 500px;
  height: 500px;
  display: block;
  grid-gap: 10px;
  overflow: auto;
  font-size: 16px;
  align-items: stretch;
  font-family: 'Open Sans';
  align-content: stretch;
  justify-items: stretch;
  justify-content: stretch;
  background-color: #af3232;
  grid-template-rows: 1;
  grid-template-columns: 3;
}
</style>
