<template>
  <div class="container">
    <LeftScreen />
    <RightScreen />
  </div>
</template>

<script>
import LeftScreen from "components/shouye/LeftScreen.vue";
import RightScreen from "components/shouye/RightScreen.vue";
export default {
  components: {
    LeftScreen,
    RightScreen,
  },
};
</script>

<style scoped>
.container {
  width: 100%;
  height: 1920px;
}
</style>
