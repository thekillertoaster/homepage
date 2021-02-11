<template>
  <b-navbar toggleable="lg" type="dark" variant="dark">
    <b-navbar-brand to="/">Toaster</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#">About</b-nav-item>
        <b-nav-item href="#">Projects</b-nav-item>
        <b-nav-item href="#">Contact</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-item to="/login">Login</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
    export default {
        name: "Navbar"
    }
</script>

<style scoped>
  .navbarlink {
    color: rgba(255, 255, 255, 0.5) !important;
  }
</style>
