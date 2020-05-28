<template>
  <div id="app">
    <Navigation />
    <router-view />
    <site-footer />
  </div>
</template>

<script>
import Navigation from "./components/Navigation.vue";
import SiteFooter from "./components/Footer.vue";
export default {
  name: "app",
  components: {
    Navigation,
    SiteFooter
  }
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Baloo+Chettan+2&display=swap");
#app {
  font-family: "Baloo Chettan 2", cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
