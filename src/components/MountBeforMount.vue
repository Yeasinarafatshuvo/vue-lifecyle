<template>
  <h1>beforeMount and Mounted {{ name }}</h1>
</template>

<script>
import { warn } from "@vue/runtime-core";
export default {
  data() {
    return {
      name: "Yeasin Arafat",
    };
  },

  //   before render html
  beforeMount() {
    console.warn("beforemount", this.$el);
  },
  //   after render html
  mounted() {
    console.warn("beforemount", this.$el);
  },
};
</script>

<style></style>
