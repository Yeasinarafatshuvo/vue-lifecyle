<template>
  <BeforeUnmountUnmounted />
</template>

<script>
import BeforeUnmountUnmounted from "./components/BeforeUnmountUnmounted.vue";

export default {
  name: "App",
  components: {
    BeforeUnmountUnmounted,
  },
};
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
