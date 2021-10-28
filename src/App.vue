<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" />
    <Layout /> -->
    <!-- <Container /> -->
    <!-- <Button /> -->
    <!-- <Link /> -->
    <!-- <Radio /> -->
    <Checkbox />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
// import Layout from "./components/Layout.vue";
// import Container from "./components/Container.vue";
// import Button from "./components/Button.vue";
// import Link from "./components/Link.vue";
// import Radio from "./components/Radio.vue";
import Checkbox from "./components/Checkbox.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    // Layout,
    // Container,
    // Button,
    // Link,
    // Radio,
    Checkbox,
  },
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
