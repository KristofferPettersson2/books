<template>
  <div>
    <h1>This is a Contact Page</h1>
    <p>{{message}}</p>
  </div>
</template>

<script>
export default {
  computed: {
    message() {
      return this.$root.message;
    },
  },
};
</script>

<style></style>
