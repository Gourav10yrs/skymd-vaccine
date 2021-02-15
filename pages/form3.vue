<template>
  <div class="container">
    <div class="container__width">
      <Logo />
      <div class="progress">
        <div class="progress__box progress__box-active"></div>
        <div class="progress__box progress__box-active"></div>
        <div class="progress__box progress__box-active"></div>
      </div>
      <form action="#" class="vaccineform">
        <label class="file">
          <img class="file__image" src="../assets/upload_image.svg" alt="Take image">
          <span>Take Photo of Insurance (Front & Back) And ID Card (Front)</span>
          <input type="file" id="fileupload" multiple>
        </label>
        <h3 class="intropage__or">OR</h3>
        <label class="file">
          <img class="file__image" src="../assets/upload.svg" alt="upload">
          <span>Upload Photo of Insurance (Front & Back) And ID Card (Front)</span>
          <input type="file" id="fileupload" multiple>
        </label>
        
      </form>
      <a class="intropage__button" type="button" href="/form4">CONTINUE</a>
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
.progress{
  display: flex;
  margin-bottom: 40px;
}
.progress__box{
  flex: 1;
  height: 12px;
  background: #E0E0E0;
  border-radius: 3px;
  margin-right: 5px;
}
.progress__box-active{
  background: #6FCF97;
}
.intropage__or {
  font-weight: 600;
  font-size: 29px;
  line-height: 29px;
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

label.file {
  position: relative;
  display: block;
  width: 100%;
  text-align: center;
  margin: 3rem 0;
  padding: 3rem;
  border: 3px dashed #D6D6D6;
  box-sizing: border-box;
  border-radius: 20px;
}

label.file:hover {
	background-color: rgba(255, 255, 255, 0.3);
}
.file__image{
  display: block;
  margin: auto;
  margin-bottom: 24px;
}
input[type=file] {
	position: absolute;
	left: 0;
	top: 0;
	width: 100%;
	height: 100%;
	opacity: 0;
	outline: 0;
}
</style>
