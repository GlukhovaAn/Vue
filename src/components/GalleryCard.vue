<template>
  <div class="gallery-card">
    <img :src="path" />
    <div class="titel">Project title</div>
    <div class="text">UI, Art direction</div>
  </div>
</template>
<script>
export default {
  name: "GalleryCardComponent",
  props: {
    path: {
      type: String,
    },
  },
};
</script>
<style scoped>
img {
  width: 350px;
}
.titel {
  font-size: 1.75rem;
  margin: 0.5rem;
}
.text {
  margin: 0.5rem;
}
</style>
