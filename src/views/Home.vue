<template>
  <div class="home">
    <Navbar />
    <v-alert type="success">ddd</v-alert>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Home",
  components: {
    Navbar,
  },
};
</script>
