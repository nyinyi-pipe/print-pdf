<template>
  <div id="app">
    <h1>Print / Export PDF</h1>
    <PrintButton />
  </div>
</template>

<script>
import PrintButton from './components/PrintButton.vue';

export default {
  name: 'App',
  components: {
    PrintButton,
  },
};
</script>

<style>
#app {
  max-width: 600px;
  margin: 0 auto;
  padding: 40px 20px;
  text-align: center;
}
</style>
