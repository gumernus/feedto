<template>
<div class="row flex-lg-row-reverse align-items-center g-5 py-5">
      <div class="col-10 col-sm-8 col-lg-6">
        <img src="@/assets/logo.png" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
      </div>
      <div class="col-lg-6">
        <h1 class="display-5 fw-bold lh-1 mb-3">Explore with friends</h1>
        <p class="lead">Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins.</p>
        <div class="d-grid gap-2 d-md-flex justify-content-md-start">
          <button type="button" class="btn btn-primary btn-lg px-4 me-md-2">Login</button>
          <button type="button" class="btn btn-outline-secondary btn-lg px-4">Sign Up</button>
        </div>
      </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Hero'
});
</script>

<style scoped>
.row{
  width: 100%;
}
.align-items-center{
  padding: 60px;
}

img{
  width: 100%;
  height: auto;
}
</style>

