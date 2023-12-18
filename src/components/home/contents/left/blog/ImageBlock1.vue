<script setup lang="ts">
import '@/assets/ir.css'
</script>

<template>
  <div class="blog-component-wrapper-1">
    <h5><span class="su">Image1</span></h5>
    <figure>
      <img className="img-normal" src="" alt="normal_image" />
    </figure>
  </div>
</template>

<style scoped>
.blog-component-wrapper-1 {
  img {
    width: 100%;
  }

  & .img-retina {
    display: none;
  }

  @media only screen and (-webkit-min-device-pixel-ratio: 1.5),
    only screen and (min-device-pixel-ratio: 1.5),
    only screen and (min-resolution: 1.5dppx) {
    .img-retina {
      display: initial;
    }

    .img-normal {
      display: none;
    }
  }
}
</style>
