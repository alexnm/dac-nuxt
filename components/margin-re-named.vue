<template>
  <div class="margin-re-named-container">
    <h1 class="margin-re-named-heading1">Heading Level 1</h1>
  </div>
</template>

<script>
export default {
  name: 'MarginReNamed',
  props: {},
}
</script>

<style scoped>
.margin-re-named-container {
  test: asdas;
  width: 500px;
  height: 500px;
  display: block;
  overflow: auto;
  font-size: 16px;
  overflow-x: auto;
  overflow-y: auto;
  font-family: 'Open Sans';
  background-color: #cc0000;
}
.margin-re-named-heading1 {
  font-size: 2em;
  margin-top: 10px;
  margin-bottom: 0.67em;
}
</style>
