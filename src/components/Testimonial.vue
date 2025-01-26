<template>
  <div>
    <div class="h1">Testimonial</div>
    <div class="cont">
        <TestimonalCard
        v-for="(el, index) in data"
        :key="index"
        :path="el.path"
        :text="el.text"
      />
    </div>
  </div>
</template>
<script>
import TestimonalCard from "./TestimonalCard.vue";
export default {
  name: "TestimonialComponent",
  components: {
    TestimonalCard,
  },
  data() {
    return {
        data: [
        {
          text:
            " This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com",
          path: "/images/testimonial.png",
        },
        {
          text:
            " This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com",
          path: "/images/testimonial.png",
        },
        {
          text:
            " This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com",
          path: "/images/testimonial.png",
        },
        {
          text:
            " This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com",
          path: "/images/testimonial.png",
        },
        {
          text:
            " This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com",
          path: "/images/testimonial.png",
        },
        {
          text:
            " This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com",
          path: "/images/testimonial.png",
        },
      ],
    }
  }
};
</script>
<style scoped>
.h1 {
  font-size: 2.5rem;
  text-align: center;
  margin: 3rem;
}
.cont {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  max-width: 1200px;
  margin: auto;
  gap: 40px;
  margin-bottom: 140px;
}
</style>
