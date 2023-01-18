<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Header emits="login"/>
    <Page />
  </div>
</template>

<script>
import Header from "./stories/Header.vue";
import Page from "./stories/Page.vue";

export default {
  name: "App",
  components: {
    Page
  }
};
</script>

<style>
@import "./index.css";
</style>
