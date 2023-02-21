<template>
  <div id="app">
    <home />
  </div>
</template>

<script>
import home from "./views/Home.vue";

export default {
  name: "App",
  components: {
    home,
  },
};
</script>

<style>
html,
body {
  width: 100%;
  overflow: hidden;
}
</style>
