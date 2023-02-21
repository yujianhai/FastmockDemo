<template>
  <div class="leftScreen"><PieChart /></div>
</template>

<script>
import PieChart from "components/common/PieCharts.vue";
export default {
  components: {
    PieChart,
  },
};
</script>

<style scoped>
.leftScreen {
  position: absolute;
  left: 0;
  width: 400px;
  height: 100%;
  border: 1px solid red;
}
</style>
