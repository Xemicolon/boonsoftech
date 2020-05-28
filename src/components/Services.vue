<template>
  <div class="services" style="font-family: 'Baloo Chettan 2', cursive;">
    <div class="container mx-auto">
      <h1 class="servicesHeading">Our Services</h1>
      <div class="px-2">
        <div class="flex flex-wrap -mx-2">
          <div class="sl">
            <div class="sl2">
              <i class="fas fa-mobile text-4xl mb-4"></i>
              <h1 class="dev">Mobile Development</h1>
              <p class="dev1">
                We build and develope cutting edge mobile application for
                android, iPhone and iPad. Our team are creative and
                knowledgeable to accomplish your individual demands as well as
                your business needs
              </p>
            </div>
          </div>
          <div class="sl">
            <div class="sl2">
              <i class="fas fa-layer-group text-4xl mb-4"></i>
              <h1 class="dev">Web Development</h1>
              <p class="dev1">
                Great user experience is critical to a success of any project
                whether it's a web-site or a business software. Our UI team will
                create professionally looking, mobile friendly, responsive
                design for you.
              </p>
            </div>
          </div>
          <div class="sl">
            <div class="rounded shadow-lg border py-8">
              <i class="fas fa-mouse text-4xl mb-4"></i>
              <h1 class="dev">Desktop Development</h1>
              <p class="dev1">
                We have outstanding experience in custom database development,
                desktop and distributed application design as well as various
                custom software components programming.
              </p>
            </div>
          </div>
        </div>
      </div>

      <button @click="viewMore" class="btn hover:bg-blue-700">View more</button>
      <hr
        style="border: 0;
    height: 3px;
    background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0));"
        class="my-10 mx-auto w-1/4"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "Services",
  methods: {
    viewMore: () => {
      window.location.href = `/services`;
    }
  }
};
</script>
<style scoped>
button:focus {
  border: none;
  outline: none;
}
</style>
