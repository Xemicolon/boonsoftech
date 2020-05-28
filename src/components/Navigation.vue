<template>
  <nav class="nav" style="font-family: 'Baloo Chettan 2', cursive;">
    <div class="nav-item">
      <a class="logo hover:text-gray-600 hover:no-underline" href="/">
        <span class="sm:text-2xl md:text-xl lg:text-2xl text-lg lg:pl-32 pl-2"
          >BOON SOFTECH</span
        >
      </a>
    </div>

    <div class="block lg:hidden">
      <button
        @click="navToggle"
        id="nav-toggle"
        class="nav-btn hover:text-gray-900 hover:border-white"
      >
        <svg
          class="fill-current h-3 w-3"
          viewBox="0 0 20 20"
          xmlns="http://www.w3.org/2000/svg"
        >
          <title>Menu</title>
          <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
        </svg>
      </button>
    </div>
    <div class="nav-content" id="nav-content">
      <ul class="list-reset lg:flex justify-end flex-1 items-center">
        <li class="mr-3">
          <router-link
            class="nav-link hover:text-gray-600 hover:text-underline"
            to="/"
            >Home</router-link
          >
        </li>
        <li class="mr-3">
          <router-link
            class="nav-link hover:text-gray-600 hover:text-underline"
            to="/about"
            >About</router-link
          >
        </li>
        <li class="mr-3">
          <router-link
            class="nav-link hover:text-gray-600 hover:text-underline"
            to="/services"
            >Services</router-link
          >
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Nav",
  methods: {
    navToggle: () => {
      document.getElementById("nav-content").classList.toggle("hidden");
    }
  }
};
</script>
