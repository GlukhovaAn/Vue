<template>
  <div class="gallerybar">
    <div class="h1">Latest Work</div>
    <div class="gallery">
      <GalleryCardComponent class="m-1" path="/images/gallery/gallery_1.png" />
      <GalleryCardComponent class="m-1" path="/images/gallery/gallery_2.png" />
      <GalleryCardComponent class="m-1" path="/images/gallery/gallery_3.png" />
      <GalleryCardComponent class="m-1" path="/images/gallery/gallery_4.png" />
      <GalleryCardComponent class="m-1" path="/images/gallery/gallery_5.png" />
      <GalleryCardComponent class="m-1" path="/images/gallery/gallery_6.png" />
    </div>
  </div>
</template>

<script>
import GalleryCardComponent from "./GalleryCard.vue";
export default {
  name: "GalleryComponent",
  components: {
    GalleryCardComponent,
  },
};
</script>
<style scoped>
.gallerybar {
    margin-bottom: 140px;
}
.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  align-items: center;
}
.h1 {
  text-align: center;
  margin: 3rem;
  margin-bottom: 0.5rem;
  font-weight: 500;
  line-height: 1.2;
  font-size: 2.5rem;
  margin-top: 0;
}
.m-1 {
  margin: 0.25rem;
}
</style>
