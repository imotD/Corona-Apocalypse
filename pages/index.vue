<template>
  <div class="Hero">
    <Nav />
    <h1 class="Hero--tagline text-uppercase">{{ title }}</h1>
    <div class="Hero--img">
      <v-img
        :aspect-ratio="2.1"
        contain
        :src="require(`../assets/img/boys.png`)"
      ></v-img>
    </div>
    <LineMenu />
  </div>
</template>

<script>
export default {
  name: "IndexPage",
  data() {
    return {
      title: "Corona Apocalyose"
    };
  }
};
</script>

<style lang="scss" scoped>
.Hero {
  position: relative;
  background-color: black;
  height: 100vh;
  &--tagline {
    color: white;
    text-align: center;
    letter-spacing: 35px;
    line-height: 140px;
    font-size: 8rem;
  }
  &--img {
    left: 0;
    right: 0;
    position: absolute;
    bottom: 0;
  }
}
</style>
