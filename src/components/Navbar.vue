<template>
<nav class="navbar fixed-top navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">FeedTo</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#"><router-link to="/">Home</router-link></a>
        </li>
        <li class="nav-item">
          <a class="nav-link"><router-link to="/about">About</router-link></a>
        </li>
      </ul>
    </div>
  </div>
</nav>
<router-view/>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Navbar'
});
</script>

<style scoped>
.navbar {
    width: 100%;
    padding: 10px;
    font-size: 17px;
}

.navbar-brand{
    font-weight: bold;
    font-size: 20px;
}

a{
    text-decoration: none;
}
a.router-link-exact-active {
  color: #42b983;
}
</style>

