<template>
  <div id="app">
    <h1>Barcode Scanner Demo</h1>
    <p>scanでスキャンが始まります<br />(カメラを許可してください)</p>
    <p>stopでスキャンを停止します</p>
    <barcode-scanner />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import BarcodeScanner from "./components/BarcodeScanner.vue";

export default Vue.extend({
  name: "App",
  components: {
    BarcodeScanner
  }
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
