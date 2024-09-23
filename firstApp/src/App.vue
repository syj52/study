<template>
  <!-- <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
  </div> -->
  <div>
    <element-view></element-view>
  </div>
</template>

<script>
import ElementView from "./views/element/ElementView.vue";
export default {
  components: { ElementView },
  data() {
    return {
      massage: "hello vue",
    };
  },
};
</script>

<style></style>
