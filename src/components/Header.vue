<template>
  <div class="header">
    <div class="subheader">
      <div class="h5">Branding | Image making</div>
      <div class="titel">Visual Designer</div>
      <p class="text">
        This is a template Figma file turned into code using Anima.<br />Learn
        more at AnimaApp.com
      </p>
      <button class="butn">Contact</button>
    </div>
    <img src="/images/header.png" />
  </div>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>

<style scoped>
.header {
  justify-content: space-between;
  margin-top: 3rem;
  display: -ms-flexbox;
  display: flex;
}
.subheader {
  display: -ms-flexbox;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 3rem;
}
img {
}
.h5 {
  font-weight: 700;
}
.titel {
  font-size: 5.5rem;
  font-weight: 300;
  line-height: 1.2;
  margin: 0.25rem;
  font-weight: bolder;
}
.text {
  margin: 0.5rem;
}
.butn {
  background-color: #343a40;
  color: rgba(255, 255, 255, 0.5);
  width: 50%;
  padding: 1rem;
  margin-top: 1.5rem;
}
</style>
