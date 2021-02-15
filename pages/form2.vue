<template>
  <div class="container">
    <div class="container__width">
      <Logo />
      <div class="progress">
        <div class="progress__box progress__box-active"></div>
        <div class="progress__box progress__box-active"></div>
        <div class="progress__box"></div>
      </div>
      <h3 class="intropage__title">Please answer the health questions below Information</h3>
      <form action="#" class="vaccineform">
        <p class="vaccineform__question">1. Are you sick today or currently in an isolation or quarantine period for COVID-19?</p>
        <div class="vaccinecheckbox">
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q1" value="Yes">
            <label class="vaccineform__label vaccinecheckbox-label" for="q1">Yes</label>
          </div>
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q1" value="No">
            <label class="vaccineform__label vaccinecheckbox-label" for="q1">No</label>
          </div>
        </div>
        <p class="vaccineform__question">2. Have you had a positive COVID-19 test in the last 3 months/90 days?</p>
        <div class="vaccinecheckbox">
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q2" value="Yes">
            <label class="vaccineform__label vaccinecheckbox-label" for="q2">Yes</label>
          </div>
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q2" value="No">
            <label class="vaccineform__label vaccinecheckbox-label" for="q2">No</label>
          </div>
        </div>
        <p class="vaccineform__question">3. Have you ever had a severe allergic reaction (e.g., anaphylaxis) to something?  For example, areaction for which you were treated with epinephrine or EpiPen®, or for which you had to go tothe hospital?</p>
        <div class="vaccinecheckbox">
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q3" value="Yes">
            <label class="vaccineform__label vaccinecheckbox-label" for="q3">Yes</label>
          </div>
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q3" value="No">
            <label class="vaccineform__label vaccinecheckbox-label" for="q3">No</label>
          </div>
        </div>
        <p class="vaccineform__question">4. Have you ever had a serious reaction after receiving a vaccine or another injectable medication?</p>
        <div class="vaccinecheckbox">
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q1" value="Yes">
            <label class="vaccineform__label vaccinecheckbox-label" for="q1">Yes</label>
          </div>
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q1" value="No">
            <label class="vaccineform__label vaccinecheckbox-label" for="q1">No</label>
          </div>
        </div>
        <p class="vaccineform__question">5 . Have you received any vaccinations in the past two weeks/14 days?</p>
        <div class="vaccinecheckbox">
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q1" value="Yes">
            <label class="vaccineform__label vaccinecheckbox-label" for="q1">Yes</label>
          </div>
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q1" value="No">
            <label class="vaccineform__label vaccinecheckbox-label" for="q1">No</label>
          </div>
        </div>
        <p class="vaccineform__question">6. Do you have a bleeding disorder or are you taking a blood thinner?</p>
        <div class="vaccinecheckbox">
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q1" value="Yes">
            <label class="vaccineform__label vaccinecheckbox-label" for="q1">Yes</label>
          </div>
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q1" value="No">
            <label class="vaccineform__label vaccinecheckbox-label" for="q1">No</label>
          </div>
        </div>
        <p class="vaccineform__question">7. Do you currently have a weakened immune system, take immunosuppressive medications, orreceive radiation or chemotherapy treatment?</p>
        <div class="vaccinecheckbox">
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q1" value="Yes">
            <label class="vaccineform__label vaccinecheckbox-label" for="q1">Yes</label>
          </div>
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q1" value="No">
            <label class="vaccineform__label vaccinecheckbox-label" for="q1">No</label>
          </div>
        </div>
        <p class="vaccineform__question">8. Are you pregnant or currently breastfeeding?</p>
        <div class="vaccinecheckbox">
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q1" value="Yes">
            <label class="vaccineform__label vaccinecheckbox-label" for="q1">Yes</label>
          </div>
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q1" value="No">
            <label class="vaccineform__label vaccinecheckbox-label" for="q1">No</label>
          </div>
        </div>
        <p class="vaccineform__question">9. Have you ever received a dose of COVID-19 vaccine?</p>
        <div class="vaccinecheckbox">
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q1" value="Yes">
            <label class="vaccineform__label vaccinecheckbox-label" for="q1">Yes</label>
          </div>
          <div class="vaccinecheckbox-div">
            <input type="checkbox" name="q1" value="No">
            <label class="vaccineform__label vaccinecheckbox-label" for="q1">No</label>
          </div>
        </div>
      </form>
      <a class="intropage__button" type="button" href="/form3">CONTINUE</a>
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
.intropage__title {
  font-weight: 600;
  font-size: 24px;
  line-height: 150%;
  color: #000;
  text-align: left;
  margin-bottom: 40px;
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

.vaccineform{
  text-align: left;
}
.vaccineform__question {
  font-weight: 600;
  font-size: 20px;
  line-height: 150%;
  margin-bottom: 40px;
  padding-top: 30px;
}
.vaccineform__label{
  display: block;
  font-size: 18px;
  line-height: 150%;
  margin-bottom: 16px;
}

.vaccinecheckbox{
  display: flex;
  margin-bottom: 40px;
  justify-content: space-between;
}
.vaccinecheckbox-div{
  flex: 1;
}
.vaccinecheckbox-label{
  display: inline;
  padding-left: 20px;  
}

input[type="checkbox"] {
  position: relative;
  width: 18px;
  height: 18px;
  border: 2px solid #333;
  border-radius: 3px;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  outline: 0;
  cursor: pointer;
}
input[type="checkbox"]::before {
  position: absolute;
  content: '';
  display: block;
  height: 10px;
  top: 1px;
  left: 4px;
  width: 6px;
  border-style: solid;
  border-color: #fff;
  border-width: 0 2px 2px 0;
  transform: rotate(45deg);
  opacity: 0;
}
input[type="checkbox"]:checked {
  color: #fff;
  border-color: #56CCF2;
  background: #56CCF2;
}
input[type="checkbox"]:checked::before {
    opacity: 1;
}

@media screen and (max-width: 325px) {
  .vaccinecheckbox {
    flex-direction: column;
  }
}


</style>
