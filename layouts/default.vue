<template>
  <div class="container">
    <NavbarVue />
    <div class="page-Container">
      <Nuxt />
    </div>
  </div>
</template>

<script>
import NavbarVue from "../components/Navbar.vue";

export default {
  components: {
    NavbarVue,
  },
};
</script>

<style>
.page-Container {
  max-width: 40em;
  margin: 0 auto;
}
</style>
