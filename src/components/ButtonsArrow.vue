<template>
  <div :class="[`buttons-arrow-1`, className || ``]">
    <div class="shop-now-1 dmsans-bold-azure-radiance-15px">{{ shopNow }}</div>
    <img
      class="right-up-1"
      src="https://anima-uploads.s3.amazonaws.com/projects/63f53caea1ccc056ea5a0736/releases/63fb6b8f1cfafcd3e751358c/img/right-up-1.svg"
      alt="right-up 1"
    />
  </div>
</template>

<script>
export default {
  name: "ButtonsArrow",
  props: ["shopNow", "className"],
};
</script>

<style>
.buttons-arrow-1 {
  align-items: center;
  align-self: center;
  background: linear-gradient(180deg, rgba(0, 157, 255, 0.1) 0%, rgba(0, 25.5, 255, 0.1) 100%);
  border-radius: 60px;
  display: flex;
  gap: 10px;
  justify-content: center;
  margin-right: 11px;
  padding: 16px 35px;
  position: relative;
  width: fit-content;
}

.shop-now-1 {
  letter-spacing: 0;
  line-height: 28px;
  margin-top: -2px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.right-up-1 {
  height: 16px;
  min-width: 16px;
  position: relative;
}

.buttons-arrow-1.buttons-arrow-2 {
  align-self: unset;
  margin-right: unset;
  padding: 11px 35px;
}

.buttons-arrow-1.buttons-arrow-3 {
  align-self: unset;
  margin-bottom: 3px;
  margin-right: unset;
  padding: 11px 35px;
}

.buttons-arrow-1.buttons-arrow {
  align-self: unset;
  border-radius: 90px;
  margin-right: unset;
  margin-top: 15px;
  width: 269px;
}
</style>
