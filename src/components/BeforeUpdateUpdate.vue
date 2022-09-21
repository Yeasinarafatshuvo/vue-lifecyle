<template>
  <h1>beforeUpdate and update</h1>
  <h1 ref="count">{{ counter }}</h1>
  <button @click="counter++">Update count</button>
</template>

<script>
export default {
  data() {
    return {
      counter: 0,
    };
  },

  beforeUpdate() {
    console.log("beforeUpdate", this.$refs["count"].textContent);
  },
  updated() {
    console.log("beforeUpdate", this.$refs["count"].textContent);
  },
};
</script>

<style></style>
