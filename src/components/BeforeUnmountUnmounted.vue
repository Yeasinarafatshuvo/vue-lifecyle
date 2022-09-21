<template>
  <button @click="show = !show">Toggle</button>

  <User v-if="show" />
</template>

<script>
import User from "./User.vue";
export default {
  components: {
    User,
  },
  data() {
    return {
      show: true,
    };
  },
};
</script>

<style></style>
