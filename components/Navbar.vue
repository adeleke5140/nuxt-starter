<template>
  <nav class="nav">
    <div class="logo">Logo</div>
    <ul>
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/news">News</NuxtLink>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "NavbarVue",
};
</script>

<style scoped>
.nav {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  color: rebeccapurple;
}

.logo {
  border: 1px solid orange;
  padding: 5px;
}
</style>
