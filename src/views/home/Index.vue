<template>
  <Content1Component />
  <Content2Component />
  <TestimoniComponent />
  <SectionFooterComponent />
</template>

<script>
import Content1Component from "@/components/Content1Component.vue";
import Content2Component from "@/components/Content2Component.vue";
import TestimoniComponent from "@/components/TestimoniComponent.vue";
import SectionFooterComponent from "@/components/SectionFooterComponent.vue";

export default {
  name: "HomePage",
    components: {
    Content1Component,
    Content2Component,
    TestimoniComponent,
    SectionFooterComponent,
  },
  mounted() {
    document.title = "Lindsay | Interview"
  }
}
</script>
