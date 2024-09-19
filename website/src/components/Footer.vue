<script setup lang="ts">

</script>

<template>
  <div id='footer'class="container-ms px-5">
    <div  class=" d-flex flex-wrap justify-content-between align-items-center py-3 my-4 border-top">
      <p class="col-md-4 mb-0 ">© 2024 Company, Inc</p>
      <Link to="/"
        class="col-md-4 d-flex align-items-center justify-content-center mb-3 mb-md-0 me-md-auto text-decoration-none">
        André Felipe
      </Link>
      <ul class="nav col-md-4 justify-content-end">
        <li class="nav-item">
          <Link to="/" class="nav-link px-2 ">Home</Link>
        </li>
        <li class="nav-item">
          <Link to="/features" class="nav-link px-2 ">Features</Link>
        </li>
        <li class="nav-item">
          <Link to="/pricing" class="nav-link px-2 ">Pricing</Link>
        </li>
        <li class="nav-item">
          <Link to="/faq" class="nav-link px-2 ">FAQs</Link>
        </li>
        <li class="nav-item">
          <Link to="/about" class="nav-link px-2 ">About</Link>
        </li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
#footer {
  width: 100%;
  background-color: var(--color-background-mute);

  position: absolute;
  bottom: 0;
}
</style>
