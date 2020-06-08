<template>
  <div>
    <b-carousel
      class="carousel-center"
      id="carousel-1"
      v-model="slide"
      :interval="3000"
      controls
      fade
      indicators
      background="#ccc"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #000;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <b-carousel-slide caption="BUILD IT">
        <template v-slot:img>
          <img
            class="d-block img-fluid h-screen w-100"
            width="1024"
            height="480"
            src="https://res.cloudinary.com/tobilite/image/upload/v1590529139/oreoluwa/slide11.jpg"
            alt="image slot"
          />
        </template>
      </b-carousel-slide>

      <b-carousel-slide caption="SCALE IT">
        <template v-slot:img>
          <img
            class="d-block img-fluid h-screen w-100"
            width="1024"
            height="480"
            src="https://res.cloudinary.com/tobilite/image/upload/v1590531900/oreoluwa/slide2.png"
            alt="image slot"
          />
        </template>
      </b-carousel-slide>

      <b-carousel-slide caption="HAPPY CUSTOMERS">
        <template v-slot:img>
          <img
            class="d-block img-fluid h-screen w-100"
            width="1024"
            height="480"
            src="https://res.cloudinary.com/tobilite/image/upload/v1590533638/oreoluwa/slide3.jpg"
            alt="image slot"
          />
        </template>
      </b-carousel-slide>

      <!-- Slide with blank fluid image to maintain slide aspect ratio -->
    </b-carousel>
  </div>
</template>

<script>
export default {
  data() {
    return {
      slide: 0,
      sliding: null
    };
  },
  methods: {
    onSlideStart() {
      this.sliding = true;
    },
    onSlideEnd() {
      this.sliding = false;
    }
  }
};
</script>
