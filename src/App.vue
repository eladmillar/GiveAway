<template>
  <section>
    <AppHeader />
    <Homepage />
  </section>
</template>

<script>
import AppHeader from "./cmps/AppHeader.vue";
import Homepage from "./views/Homepage.vue";

export default {
  created() {
    console.log("Vue App created");
  },
  components: {
    AppHeader,
    Homepage
  }
};
</script>