<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/peiko-logo-mini.png" />
    <h1>Test</h1>
    <hr />
    <stock-table></stock-table>
    <the-footer></the-footer>
  </div>
</template>

<script>
import StockTable from "./components/StockTable"
import TheFooter from "./components/TheFooter";

export default {
  components: {StockTable, TheFooter},
  name: "App",
};
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
