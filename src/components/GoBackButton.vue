<template>
  <button @click="goBack">
    Go Back
  </button>
</template>

<script>
export default {
  name: "GoBackButton",
  methods: {
    goBack() {
      this.$router.back();
    },
  },
};
</script>

<style scoped>
.btn {
  margin-top: 20px;
  padding: 10px 20px;
  background-color: #2c3e50;
  color: white;
  border: none;
  cursor: pointer;
}

.btn:hover {
  background-color: #1a252f;
}
</style>