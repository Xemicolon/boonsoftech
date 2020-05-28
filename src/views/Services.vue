<template>
  <div class="services w-full mx-auto">
    <home-hero />
    <div class="container mx-auto">
      <h1 class="text-3xl font-bold mt-20 mb-10">WHAT WE DO</h1>
      <div class="px-2">
        <div class="flex flex-wrap -mx-2">
          <div class="w-full mb-8 lg:w-1/3 xl:w-1/3 px-2">
            <div class="rounded shadow-lg border py-8">
              <i class="fas fa-mobile text-4xl mb-4"></i>
              <h1 class="text-2xl font-bold mb-4">Mobile Development</h1>
              <p class="text-xl px-4 tracking-wider">
                We build and develope cutting edge mobile application for
                android, iPhone and iPad. Our team are creative and
                knowledgeable to accomplish your individual demands as well as
                your business needs
              </p>
            </div>
          </div>
          <div class="w-full mb-8 lg:w-1/3 xl:w-1/3 px-2">
            <div class="rounded shadow-lg border py-8">
              <i class="fas fa-layer-group text-4xl mb-4"></i>
              <h1 class="text-2xl font-bold mb-6">Web Development</h1>
              <p class="text-xl px-4 tracking-wider">
                Great user experience is critical to a success of any project
                whether it's a web-site or a business software. Our UI team will
                create professionally looking, mobile friendly, responsive
                design for you.
              </p>
            </div>
          </div>
          <div class="w-full lg:w-1/3 xl:w-1/3 px-2">
            <div class="rounded shadow-lg border py-8">
              <i class="fas fa-mouse text-4xl mb-4"></i>
              <h1 class="text-2xl font-bold mb-4">Desktop Development</h1>
              <p class="text-xl px-4 tracking-wider">
                We have outstanding experience in custom database development,
                desktop and distributed application design as well as various
                custom software components programming.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <Contact />
  </div>
</template>

<script>
import HomeHero from "@/components/HomeHero.vue";
import Contact from "@/components/Contact.vue";
export default {
  components: {
    HomeHero,
    Contact
  }
};
</script>

<style scoped></style>
