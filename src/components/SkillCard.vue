<template>
  <div
    class="card"
  >
    <img class="img" :src="path" />
    <div class="h3">{{ title }}</div>
    <div class="text">{{ description }}</div>
  </div>
</template>
<script>
export default {
  name: "SkillCard",
  props: {
    title: {
      type: String,
    },
    description: {
      type: String,
    },
    path: { type: String },
  },
};
</script>
<style scoped>
.img {
  width: 200px;
  height: 200px;
}
.card {
  display: flex;
  justify-content: space-around;
  flex-direction: column;
  align-items: center;
}
.h3 {
  font-size: 1.75rem;
  margin: 1rem;
}
.text {
  text-align: center;
}
</style>
