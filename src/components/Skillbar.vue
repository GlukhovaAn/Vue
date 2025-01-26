<template>
  <div class="skill">
    <SkillCard
        v-for="(el, index) in data"
        :key="index"
        :path="el.path"
        :title="el.title"
        :description="el.description"
      />
  </div>
</template>
<script>
import SkillCard from "./SkillCard.vue";
export default {
  name: "SkillbarComponent",
  data() {
    return {
      data: [
        {
          description:
            "This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com",
          title: "Product Design",
          path: "/images/skills/product.png",
        },
        {
          description:
            "This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com",
          title: "Visual Design",
          path: "/images/skills/visual.png",
        },
        {
          description:
            "This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com",
          title: "Art Direction",
          path: "/images/skills/art.png",
        },
      ],
    };
  },
  components: {
    SkillCard,
  },
};
</script>
<style scoped>
.skill {
  display: flex;
  justify-content: space-around;
  margin-bottom: 140px;
}
</style>
