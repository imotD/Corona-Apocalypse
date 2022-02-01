<template>
  <div class="sosmed">
    <div class="sosmed--line"></div>
    <div class="sosmed--text">Contact</div>
  </div>
</template>

<script>
export default {
  name: "LineMenuItem"
};
</script>

<style lang="scss" scoped>
.sosmed {
  position: absolute;
  bottom: 0;
  left: 70px;
  right: 70px;
  height: 100px;
  &--line {
    &::before {
      position: absolute;
      top: 0;
      width: 1px;
      border-radius: 100px;
      height: 50px;
      background: white;
      content: " ";
    }
  }

  &--text {
    position: absolute;
    transform: rotate(270deg);
    color: white;
    top: -3.5rem;
    left: -2rem;
  }
}
</style>
