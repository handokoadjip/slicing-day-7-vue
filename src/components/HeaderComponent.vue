<template>
  <header class="py-3 px-3 px-lg-0">
    <nav class="navbar navbar-expand-lg navbar-light">
      <div class="container px-0">
        <router-link class="fw-medium navbar-brand me-5 fs-2" to="#">
          chilli
        </router-link>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav text-uppercase d-flex align-items-center ms-auto fw-bold">
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link" aria-current="page" to="#">work</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link" to="#">about</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link" to="#">news</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link line py-2 px-4" to="#">contact</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link line py-2 px-4" to="#">en</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

