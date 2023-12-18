<script setup lang="ts"></script>

<template>
  <div class="blog-component-wrapper-2">
    <div class="img-retina" />
  </div>
</template>

<style scoped>
.blog-component-wrapper-2 {
  margin-top: 15px;

  & p {
    padding-top: 5px;
  }
}

.img-retina {
  & h5 {
    color: #fff;
    text-align: center;
    padding: 30px 30px;
    text-transform: uppercase;
  }

  height: 220px;
  background: no-repeat center / cover
    url('');

  @media only screen and (-webkit-min-device-pixel-ratio: 2),
    only screen and (min-device-pixel-ratio: 2),
    only screen and (min-resolution: 2dppx) {
    background-image: url('');
  }

  @media only screen and (-webkit-min-device-pixel-ratio: 3),
    only screen and (min-device-pixel-ratio: 3),
    only screen and (min-resolution: 3dppx) {
    background-image: url('');
  }
}
</style>
