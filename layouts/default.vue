<template>
  <div>
    <Header />
    <!-- <h1>Default header</h1> -->
    <Nuxt />
  </div>
</template>
<script>
import Header from "~/components/Header.vue";
// import Header from "../components/Header.vue";

export default {
  components: { Header }
};
</script>
