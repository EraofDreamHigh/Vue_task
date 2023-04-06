<template>
  <div :class="[`inner-item-1`, className || ``]">
    <img
      class="cv-1"
      src="https://anima-uploads.s3.amazonaws.com/projects/63f53caea1ccc056ea5a0736/releases/63fb6b8f1cfafcd3e751358c/img/cv-1.svg"
      alt="cv 1"
    />
    <div class="post-your-first-breadwinner dmsans-medium-log-cabin-20px">{{ postAJob }}</div>
    <p class="sign-up-for-free-se dmsans-normal-log-cabin-15px">
      Sign up for free, set up your Bread winner, and offer your work to our global audience.
    </p>
  </div>
</template>

<script>
export default {
  name: "X1",
  props: ["postAJob", "className"],
};
</script>

<style>
.inner-item-1 {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  min-height: 185px;
  width: 294px;
}

.cv-1 {
  height: 40px;
  width: 40px;
}

.post-your-first-breadwinner {
  letter-spacing: 0;
  line-height: normal;
  margin-top: 20px;
  min-height: 26px;
}

.sign-up-for-free-se {
  letter-spacing: 0;
  line-height: 28px;
  margin-top: 15px;
  min-height: 84px;
  width: 290px;
}

.inner-item-1.x4-1 {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  min-height: 157px;
  width: 294px;
}

.inner-item-1.x4-1 .sign-up-for-free-se {
  min-height: 56px;
}
</style>
