<template>
  <div class="home">
    <Nav class="mb-6" />
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" class="text-center" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Nav from "@/components/Nav.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    Nav,
  },
};
</script>
