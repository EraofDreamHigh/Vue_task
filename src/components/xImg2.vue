<template>
  <div :class="[`img-6`, className || ``]"><img class="surface-3" :src="surface3" alt="Surface 3" /></div>
</template>

<script>
export default {
  name: "xImg2",
  props: ["surface3", "className"],
};
</script>

<style>
.img-6 {
  align-items: flex-start;
  background-image: url(https://anima-uploads.s3.amazonaws.com/projects/63f53caea1ccc056ea5a0736/releases/63fa72666926d76ba3d3dfe8/img/ellipse-76@2x.png);
  background-size: 100% 100%;
  display: flex;
  margin-left: -1956px;
  margin-top: -1892.9px;
  min-width: 90px;
}

.surface-3 {
  height: 90px;
  object-fit: cover;
  width: 90px;
}

.img-6.img-7 {
  margin-left: -2313px;
  margin-top: -1893px;
}

.img-6.img-8 {
  margin-left: -2670px;
}

.img-6.img-9 {
  margin-left: -3027px;
}
</style>
