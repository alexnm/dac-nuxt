<template>
  <div class="page-renamed-container">
    <app-component headingle="What the hell?"></app-component>
    <margin-re-named></margin-re-named>
  </div>
</template>

<script>
import AppComponent from '../components/component'
import MarginReNamed from '../components/margin-re-named'

export default {
  name: 'PageRenamed',
  components: {
    AppComponent,
    MarginReNamed,
  },
  head: {
    title: 'dac',
  },
}
</script>

<style scoped>
.page-renamed-container {
  width: 100%;
  display: block;
  font-size: 16px;
  min-height: 100%;
  font-family: 'Open Sans';
  background-color: #fcfcfc;
}
</style>
