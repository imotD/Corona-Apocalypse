<template>
  <div class="Hero">
    <Nav />
    <Hero :title="title" />
    <LineMenu />
  </div>
</template>

<script>
export default {
  name: "HeaderItem",
  data() {
    return {
      title: "Corona Apocalyose"
    };
  }
};
</script>

<style lang="scss" scoped></style>
