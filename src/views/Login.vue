<template>
  <div>
    <AppHeader />
    <h2>Login</h2>
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