<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="タイトルを編集してみた" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Header from "./"

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
