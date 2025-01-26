<template>
  <nav class="nav">
    <div class="logo">Logo</div>
    <div class="nav-items">
      <div class="nav-item">About</div>
      <div class="nav-item">Work</div>
      <div class="nav-item">Contact</div>
    </div>
  </nav>
</template>
<script>
export default {
  name: "AppNavbar",
  data() {
    return {
      name: "navbar",
    };
  },
};
</script>
<style scoped>
.nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #fff;
  padding: 1rem;
}
.logo {
  padding: 0.5rem;
}
.nav-items {
  padding: 0.5rem;
  display: flex;
}
.nav-item {
  padding: 0.5rem;
  font-weight: 700;
}
</style>
