<template>
  <div class="container">
    <h1>About</h1>
    <p>This is a demonstration on how Vue Router navigation's and page routing.</p>
    <GoBackButton />
  </div>
</template>

<script>
import GoBackButton from "@/components/GoBackButton.vue";

export default {
  components: {
    GoBackButton,
  },
};
</script>
