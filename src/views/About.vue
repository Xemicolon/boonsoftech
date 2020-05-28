<template>
  <div class="about">
    <div class="container mx-auto mt-40 w-full">
      <h1 class="text-4xl font-semibold tracking-widest mb-10">About</h1>
      <hr
        style="border: 0;
    height: 3px;
    background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0));"
        class="mt-10 mb-16 mx-auto w-1/4"
      />
      <p class="tracking-wider text-2xl mx-auto">
        Our team of experts writes software for our clients who have a critical
        need to achieve digital transformation.The transformative effect of
        digitalization allows our clients to benefit from automation
        efficiencies rather than simply enhancing conventional business methods.
        BOON SOFTECH’s clients can expand and grow their business’ reach in new
        and previously unforeseen ways due to the scalability and flexibility
        built into every BOON SOFTECH project. BOON SOFTECH’s Digital
        Transformation methodology allows our customers to achieve cost
        certainty and predictable outcomes when forecasting business growth and
        expansion.
      </p>

      <Contact />
    </div>
  </div>
</template>

<script>
import Contact from "@/components/Contact.vue";
export default {
  name: "About",
  components: {
    Contact
  }
};
</script>
