<template>
      <div class="social-media mt-3 mb-3">
        <img :src="require('@/assets/github.svg')">
        <img :src="require('@/assets/linkedin.svg')">
        <img :src="require('@/assets/blogger.svg')">
        <img :src="require('@/assets/pinterest.svg')">
        <img :src="require('@/assets/mail.svg')">
      </div>
</template>
<style>
.social-media {
  display: flex;
  gap: 2rem;
  justify-content: center;
  flex-wrap: wrap;
}
.social-media img {
  width: 1rem;
  height: 1rem;
  filter: invert(80%) sepia(33%) saturate(2658%) hue-rotate(191deg) brightness(97%) contrast(93%);
}
</style>