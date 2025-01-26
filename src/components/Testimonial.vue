<template>
  <div>
    <div class="h1">Testimonial</div>
    <div class="cont">
      <div class="card">
        <p>
          This is a template Figma file,<br />
          turned into code using Anima.<br />
          Learn more at AnimaApp.com
        </p>
        <img src="/images/testimonial.png" class="img" />
      </div>
      <div class="card">
        <p>
          This is a template Figma file,<br />
          turned into code using Anima.<br />
          Learn more at AnimaApp.com
        </p>
        <img src="/images/testimonial.png" class="img" />
      </div>
      <div class="card">
        <p>
          This is a template Figma file,<br />
          turned into code using Anima.<br />
          Learn more at AnimaApp.com
        </p>
        <img src="/images/testimonial.png" class="img" />
      </div>
      <div class="card">
        <p>
          This is a template Figma file,<br />
          turned into code using Anima.<br />
          Learn more at AnimaApp.com
        </p>
        <img src="/images/testimonial.png" class="img" />
      </div>
      <div class="card">
        <p>
          This is a template Figma file,<br />
          turned into code using Anima.<br />
          more at AnimaApp.com
        </p>
        <img src="/images/testimonial.png" class="img" />
      </div>
      <div class="card">
        <p>
          This is a template Figma file,<br />
          turned into code using Anima.<br />
          Learn more at AnimaApp.com
        </p>
        <img src="/images/testimonial.png" class="img" />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "TestimonialComponent",
};
</script>
<style scoped>
.img {
  width: 310px;
  height: 88px;
}
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
.card {
  padding: 30px;
  flex-direction: column;
  display: flex;
  align-items: center;
  background-color: #f8f9fa;
}
</style>
