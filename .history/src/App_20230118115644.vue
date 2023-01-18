<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="タイトルを編集してみた" />
    <Header />
    <Page />
  </div>
</template>

<script>
import Header from "./stories/Header.vue";
import Page from "./stories/Page.vue";

export default {
  name: "App",
  components: {
    Header,
    Page
  }
};
</script>

<style>
@import "./index.css";
</style>
