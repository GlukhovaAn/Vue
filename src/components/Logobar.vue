<template>
  <div class="logobar">
    <img
      v-for="(logo, index) in logos"
      :key="index"
      :src="logo"
      :alt="'Logo ' + index"
      class="logo"
    />
  </div>
</template>
<script>
export default {
  name: "LogobarComponent",
  props: {
    logos: {
      type: Array,
      required: true,
    },
  },
};
</script>

<style>
.logo {
  width: 100px;
  height: 50px;
  object-fit: contain;
}
.logobar {
  display: flex;
  justify-content: space-around;
  margin-top: 0.5rem;
  flex-wrap: wrap;
  margin: 140px 0;
}
</style>
