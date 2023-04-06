<template>
  <div :class="[`img-4`, className || ``]">
    <img class="rectangle-210" :src="rectangle210" alt="Rectangle 210" />
    <div class="overlap-group-7" :style="{ 'background-image': 'url(' + overlapGroup + ')' }">
      <img
        class="rectangle-212-1"
        src="https://anima-uploads.s3.amazonaws.com/projects/63f53caea1ccc056ea5a0736/releases/63fb6b8f1cfafcd3e751358c/img/rectangle-212-1.svg"
        alt="Rectangle 212"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "xImg",
  props: ["rectangle210", "overlapGroup", "className"],
};
</script>

<style>
.img-4 {
  align-items: flex-end;
  display: flex;
  gap: 1436px;
  height: 300px;
  left: 0;
  min-width: 260px;
  position: absolute;
  top: 0;
}

.rectangle-210 {
  height: 300px;
  margin-bottom: -2605px;
  margin-left: -1696px;
  width: 260px;
}

.overlap-group-7 {
  align-items: flex-end;
  background-position: 50% 50%;
  background-size: cover;
  display: flex;
  min-width: 260px;
}

.rectangle-212-1 {
  height: 300px;
  width: 260px;
}
</style>
