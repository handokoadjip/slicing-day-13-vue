<template>
  <footer class="py-5 px-4 border-top-fade-black-1">
    <div class="container-fluid">
      <div class="row w-100 pt-5">
        <div class="col-lg-2 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start">
            <nav>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">About</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Events</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Contacts</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Contribtions</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Advertising</router-link>
            </nav>
          </div>
        </div>
        <div class="col-lg-2 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start">
            <nav>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Facebook</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Instagram</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Twitter</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Pinterest</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">LinkedIn</router-link>
            </nav>
          </div>
        </div>
        <div class="col-lg-4 mb-5 mb-lg-0 ms-auto">
          <div class="wrapper text-center d-flex flex-column justify-content-between h-100">
            <h3 class="fs-6 fw-medium text-fade-black-1 mb-4 text-center text-lg-end">
              Lorem ipsum dolor sit amet.
              <br />
              Lorem, ipsum dolor.
            </h3>
            <form action="">
              <input class="form-control form-control-lg" type="text" placeholder="Let's stay in touch">
            </form>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>