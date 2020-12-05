<template>
  <div id="app">
    <Header />
    <router-view />
  </div>
</template>

<script>
import M from "materialize-css";
import Header from "./components/Header";
export default {
  mounted() {
    M.AutoInit();
  },
  components: {
    Header,
  },
};
</script>