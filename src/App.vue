<template>
<Navbar></Navbar>
</template>

<script>
import Navbar from "@/components/Navbar.vue"

import "bootstrap/dist/css/bootstrap.min.css";

export default {
  name: "App",
  components: {
    Navbar
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

</style>
