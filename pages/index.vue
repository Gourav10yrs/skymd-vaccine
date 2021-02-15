<template>
  <div class="container">
    <div class="container__width">
      <Logo />
      <h3 class="intropage__title">Moderna Covid - 19 Vaccine Information and Consent Form</h3>
      <p class="intropage__text">- Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,</p>
      <p class="intropage__text">- When an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting,</p>
      <p class="intropage__text">- Remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages</p>
      <p class="intropage__text">- More recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
      <a class="intropage__button" type="button" href="/form">Enroll For Vaccine</a>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  text-align: center;
  position: relative;
}
.container__width{
  width: min(540px, 90%);
}
.intropage__title {
  font-weight: 600;
  font-size: 24px;
  line-height: 150%;
  color: #000;
  text-align: left;
  margin-bottom: 40px;
}
.intropage__text{
  text-align: left;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 160%;
  margin-bottom: 30px;
}
.intropage__button{
  text-transform: uppercase;
  background: #F2994A;
  color: #fff;
  text-decoration: none;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  font-size: 18px;
  line-height: 150%;
  height: 70px;
  margin-bottom: 49px;
}
</style>
