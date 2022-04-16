<template>
  <header class="mb-5">
    <nav class="navbar navbar-light px-4">
      <div class="container-fluid px-0 d-flex justify-content-between">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="navbar-brand d-flex align-items-center">
          <router-link class="fs-3 fw-bolder text-uppercase me-3 pe-3 border-end" to="#">lindsay</router-link>
          <router-link class="fs-6 text-muted fw-bolder" to="#">everyone</router-link>
        </div>

        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav text-uppercase">
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" aria-current="page" to="#">work</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">home</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">about</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">contact</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <section class="px-4">
      <div class="container-fluid">
        <div class="row min-vh-80 pb-5">
          <div class="col-lg-10">
            <div class="wrapper d-flex align-items-end h-100">
              <h1 class="text-navbar pb-4 display-2 ff-slobo">Working as a Literary Agent in New York-a City Where
                BooksLive and Breathe</h1>
            </div>
          </div>
        </div>
      </div>
    </section>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

