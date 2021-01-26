<template>
  <div id="app">
    <app-header></app-header>
    <app-main></app-main>
    <app-footer></app-footer>
  </div>
</template>

<script>
import AppHeader from "./components/Header"
import AppFooter from "./components/Footer"
import AppMain from "@/views/Main"
export default {
  name: 'App',
  components: {
    AppFooter,
    AppHeader,
    AppMain
  }
}
</script>

<style lang="scss">
@import "./assets/fonts.css";
html {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  overflow: hidden;
  body {
    #app {
      font-family: 'HelveticaRegular';
      font-size: 14px;
    }
  }
}
</style>
