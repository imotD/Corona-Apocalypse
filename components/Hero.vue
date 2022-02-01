<template>
  <div>
    <h1 class="Hero--tagline text-uppercase">{{ title }}</h1>
    <div class="Hero--img">
      <v-img
        :aspect-ratio="2.1"
        contain
        :src="require(`../assets/img/boys.png`)"
      ></v-img>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeroIndex",
  props: ["title"]
};
</script>
