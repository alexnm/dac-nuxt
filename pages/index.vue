<template>
  <div class="index-container">
    <margin-re-named></margin-re-named>
    <nuxt-link to="/page-renamed" class="index-navlink">Go there</nuxt-link>
  </div>
</template>

<script>
import MarginReNamed from '../components/margin-re-named'

export default {
  name: 'Page',
  components: {
    MarginReNamed,
  },
  head: {
    title: 'dac',
  },
}
</script>

<style scoped>
.index-container {
  width: 100%;
  height: 100%;
  display: block;
  padding: 10px;
  position: static;
  overflow-x: auto;
  overflow-y: auto;
  font-family: Open Sans;
  background-color: #fcfcfc;
}
.index-navlink {
  color: #000;
  cursor: pointer;
  text-decoration: underline;
}
</style>
