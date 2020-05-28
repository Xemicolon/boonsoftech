<template>
  <div class="home">
    <home-hero />
    <homeComponent />
    <services />
    <contact />
  </div>
</template>

<script>
// @ is an alias to /src
import HomeComponent from "@/components/HomeComponent.vue";
import HomeHero from "@/components/HomeHero.vue";
import Services from "@/components/Services.vue";
import Contact from "@/components/Contact.vue";

export default {
  name: "Home",
  components: {
    HomeComponent,
    HomeHero,
    Services,
    Contact
  }
};
</script>
