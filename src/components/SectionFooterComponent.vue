<template>
  <section class="mb-5 pt-5 px-4">
    <div class="container-fluid">
      <div class="row justify-content-end">
        <div class="col-lg-6">
          <div class="wrapper w-100 d-flex justify-content-between border-bottom-fade-black-1">
            <p class="mb-0">Let's stay in touch</p>
            <router-link to="#">
              <p class="mb-0">Subscribe</p>
            </router-link>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="mb-5 pt-5 px-4">
    <div class="container-fluid">
      <div class="row justify-content-end">
        <div class="col-lg-12">
          <div class="wrapper w-100 d-flex justify-content-between">
            <router-link to="#">
              <i class="fas fa-3x fa-angle-left"></i>
            </router-link>
            <router-link to="#">
              <i class="fas fa-3x fa-angle-right"></i>
            </router-link>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="mb-5 py-5 px-4">
    <div class="container-fluid">
      <div class="row justify-content-end">
        <div class="col-lg-12 text-center">
          <p>
            View More:&nbsp;
            <router-link to="#">
              <u>Businness</u>
            </router-link>
            ,{{" "}}
            <router-link to="">
              <u>Interview</u>
            </router-link>
            ,{{" "}}
            <router-link to="">
              <u>New York</u>
            </router-link>
            ,{{" "}}
            <router-link to="">
              <u>USA</u>
            </router-link>
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SectionFooterComponent",
}
</script>