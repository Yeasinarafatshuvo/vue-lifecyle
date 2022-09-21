<template>
  <h1>beforeCreated and created {{ name }}</h1>
</template>

<script>
export default {
  data() {
    console.warn("created");
    return {
      name: "Yeasin Arafat",
    };
  },
  //Before load side
  beforeCreate() {
    this.name = "yeasin";
    alert("beforeCreated");
  },
  //   after load side
  created() {
    this.name = "arafat";
    alert("created");
  },
};
</script>

<style></style>
