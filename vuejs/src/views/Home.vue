<template>
  <div class="home grid">
    <div class="site-title">Home</div>
    <div class="site-description">Use the above navbar to choose if you want to submit an image or a video.</div>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from "vue-property-decorator";

@Component
export default class Home extends Vue {}
</script>

<style lang="scss" scoped>
$gap-title: 36px;

.home {
  height: 100%;
  width: 100%;

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  .site-description {
    margin-top: $gap-title;
  }
}
</style>
