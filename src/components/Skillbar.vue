<template>
  <div class="skill">
    <SkillCard
      title="Product Design"
      :description="description"
      path="/images/skills/product.png"
    />
    <SkillCard
      title="Visual Design"
      :description="description"
      path="/images/skills/visual.png"
    />
    <SkillCard
      title="Art Direction"
      :description="description"
      path="/images/skills/art.png"
    />
  </div>
</template>
<script>
import SkillCard from "./SkillCard.vue";
export default {
  name: "SkillbarComponent",
  data() {
    return {
      description:
        "This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com",
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
