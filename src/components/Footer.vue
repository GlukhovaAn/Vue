<template>
  <div class="section">
    <div class="h3">Lets work together</div>
    <div class="footer">
      <div class="footersect-1">
        <p class="footersect-1-p">
          This is a template Figma file, turned into code using Anima. Learn
          more at AnimaApp.com This is a template Figma file, turned into code
          using Anima. Learn more at AnimaApp.com
        </p>
        <div class="img-section">
          <img class="img" src="/images/footer/discord.png" />
          <img class="img" src="/images/footer/facebook.png" />
          <img class="img" src="/images/footer/dribble.png" />
          <img class="img" src="/images/footer/instagram.png" />
          <img class="img" src="/images/footer/behance.png" />
        </div>
      </div>
      <div class="form">
        <input class="form-input" type="text" placeholder="Name" />
        <input class="form-input" type="text" placeholder="Email" />
        <button class="form-btn">Submit</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterComponent",
};
</script>
<style scoped>
.section {
  padding: 0.5rem;
  margin: 20px;
}
.h3 {
  text-align: left;
  margin-bottom: 20px;
  font-size: 20px;
}
.footer {
  flex-direction: row;
  display: flex;
  justify-content: space-between;
}
.footersect-1 {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  width: 50%;
}
.footersect-1-p {
  text-align: left;
}
.img-section {
  display: flex;
}
.img {
  width: 30px;
  height: 30px;
  margin: 0.5rem;
}
.form {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  width: 40%;
}
.form-input {
  background-color: #f8f9fa;
  border: 0;
  padding: 16px 24px;
  margin-bottom: 10px;
}
.form-btn {
  background-color: #2d2d2d;
  padding: 0.5rem;
  color: #f8f9fa;
  padding: 24px 64px;
  width: 200px;
}
</style>
