<template>
  <div id="app">
    <tempcom></tempcom>
  </div>
</template>

<script>
import tempcom from "./components/tempcom";

export default {
  name: "app",

  components: {
    tempcom
  },
  data() {
    return {};
  }
};
</script>

<style lang="scss">
@import "./style/style.scss";
</style>
