<template>
  <div class="card">
    <p>{{ text }}</p>
    <img :src="path" class="img" />
  </div>
</template>
<script>
export default {
  name: "TestimonalCard",
  props: {
    text: {
      type: String,
    },
    path: { type: String },
  },
};
</script>
<style scoped>
.img {
  width: 310px;
  height: 88px;
}
.card {
  flex-direction: column;
  display: flex;
  align-items: center;
  background-color: #f8f9fa;
  max-width: 30%;
  padding: 30px;
}
.card p {
  max-width: 200px;
}
</style>
