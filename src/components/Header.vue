<template>
  <nav class="deep-orange darken-1 my_Nav" role="navigation">
    <div class="nav-wrapper container">
      <a id="logo-container" href="#" class="brand-logo">Student Equipment</a>
      <ul class="right hide-on-med-and-down">
        <li><router-link to="/home">Home</router-link></li>
        <li>
          <router-link to="/cart">Cart<sub>(3)</sub></router-link>
        </li>
        <li><router-link to="/profile">Profile</router-link></li>
        <li><router-link to="/">Log out</router-link></li>
      </ul>

      <ul id="nav-mobile" class="sidenav">
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/login">Login</router-link></li>
        <li><router-link to="/cart">Cart</router-link></li>
      </ul>
      <a href="#" data-target="nav-mobile" class="sidenav-trigger"
        ><i class="material-icons">menu</i></a
      >
    </div>
  </nav>
</template>

<script>
export default {
  name: "Header",
};
</script>