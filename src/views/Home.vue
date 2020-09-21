<template>
  <div>
    <AppHeader />
    <h2>Welcome Home</h2>
  </div>
</template>

<script>
import AppHeader from "../components/AppHeader";

export default {
  name: "home",
  components: {
    AppHeader,
  },
};
</script>

<style scoped>
h2 {
  color: green;
}
</style>