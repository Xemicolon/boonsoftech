<template>
  <div class="contact" style="font-family: 'Baloo Chettan 2', cursive;">
    <div class="container">
      <h1 class="getintouch">Get In Touch!</h1>
      <div class="px-4">
        <div class="flex flex-wrap -mx-4">
          <div class="git">
            <a @click="phone" style="cursor: pointer">
              <div class="rounded shadow-lg border-2 py-10">
                <i class="fas fa-phone text-4xl mb-4"></i>
                <p class="gitt">080808080808</p>
              </div>
            </a>
          </div>
          <div class="git">
            <a @click="mail" style="cursor: pointer">
              <div class="rounded shadow-lg border-2 py-10">
                <i class="fas fa-envelope text-4xl mb-4"></i>
                <p class="gitt">Hello@123.com</p>
              </div>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact",
  methods: {
    mail: () => {
      window.location.href = "mailto:hello@123.com";
    },
    phone: () => {
      window.location.href = "tel:+23480808080";
    }
  }
};
</script>
<style scoped></style>
