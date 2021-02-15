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
        <div class="vaccineform__upload">
          <img class="vaccineform__upload-image" src="../assets/upload_image.svg" alt="Take image">
          <span class="vaccineform__upload-filename">Insurance Front.jpg</span>
          <span class="vaccineform__statusBox">
            <span class="vaccineform__status vaccineform__status-done"></span>
            <span class="vaccineform__status vaccineform__status-delete"></span>    
          </span>
        </div>
        <div class="vaccineform__upload">
          <img class="vaccineform__upload-image" src="../assets/upload_image.svg" alt="Take image">
          <span class="vaccineform__upload-filename">Insurance Back.jpg</span>
          <span class="vaccineform__statusBox">
            <span class="vaccineform__status vaccineform__status-pause"></span>
            <span class="vaccineform__status vaccineform__status-close"></span>    
          </span>
        </div>
        <div class="vaccineform__upload">
          <img class="vaccineform__upload-image" src="../assets/upload_image.svg" alt="Take image">
          <span class="vaccineform__upload-filename">ID Card Front.jpg</span>
          <span class="vaccineform__statusBox">
            <span class="vaccineform__status vaccineform__status-pause"></span>
            <span class="vaccineform__status vaccineform__status-close"></span>    
          </span>
        </div>
      </form>
      <a class="intropage__button" type="button" href="/form5">CONTINUE</a>
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
.intropage{
  margin: 0 29px;
  margin-bottom: 49px;
}
.vaccineform__upload{
  background: rgba(92, 176, 249, 0.07);
  border: 2px solid #D6D6D6;
  box-sizing: border-box;
  border-radius: 15px;
  margin-bottom: 20px;
  display: flex;
  align-items: center;
  padding: 24px;
  justify-content: space-between;
}
.vaccineform__upload-image{
  height: 26px;
  padding-right: 10px;
}
.vaccineform__upload-filename {
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}
.vaccineform__statusBox {
  display: inherit;
}
.vaccineform__status {
  height: 25px;
  width: 25px;
  border-radius: 50%;
  margin-right: 5px;
}
.vaccineform__status-done {
  background: rgba(111, 207, 151, 0.1);
}
.vaccineform__status-done::before{
  content: url(../assets/check.svg);
  display: inline-flex;
  height: 100%;
}
.vaccineform__status-delete{
  background: rgba(51, 51, 51, 0.11);
}
.vaccineform__status-delete::before {
  content: url(../assets/delete.svg);
  display: inline-flex;
  height: 100%;
}
.vaccineform__status-pause {
  background: rgba(196, 196, 196, 0.2);
}
.vaccineform__status-pause::before {
  content: url(../assets/pause.svg);
  display: inline-flex;
  height: 100%;
}
.vaccineform__status-close{
  background: rgba(247, 78, 69, 0.09);
}
.vaccineform__status-close::before {
  content: url(../assets/close.svg);
  display: inline-flex;
  height: 100%;
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
