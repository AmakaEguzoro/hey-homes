<template>
  <div id="app">
    <home />
    <specialties />
    <choice />
    <testimonials />
  </div>
</template>

<script>
import Home from "./components/Home.vue";
import Specialties from "./components/Specialties.vue";
import Choice from "./components/Choice.vue";
import Testimonials from "./components/Testimonials.vue";

export default {
  name: "App",
  components: {
    Home,
    Specialties,
    Choice,
    Testimonials,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700;900&display=swap");
</style>
