<template>
  <div class="container">
    <div class="container__width">
      <Logo />
      <div class="progress">
        <div class="progress__box progress__box-active"></div>
        <div class="progress__box"></div>
        <div class="progress__box"></div>
      </div>
      <h3 class="intropage__title">Information</h3>
      <form action="#" class="vaccineform">
        <label class="vaccineform__label vaccineform__label-required" for="name">Name</label>
        <input class="vaccineform__input" type="text" id="name">
        <label class="vaccineform__label vaccineform__label-required" for="phone">Mobile Phone</label>
        <input class="vaccineform__input" type="number" id="phone">
        <label class="vaccineform__label vaccineform__label-required" for="address">Address</label>
        <input class="vaccineform__input" type="text" id="address">
        <label class="vaccineform__label vaccineform__label-required" for="city">City</label>
        <input class="vaccineform__input" type="text" id="city">
        <label class="vaccineform__label vaccineform__label-required" for="name">State</label>
        <input class="vaccineform__input" type="text" id="name">
        <label class="vaccineform__label vaccineform__label-required" for="zipcode">Zipcode</label>
        <input class="vaccineform__input" type="number" id="zipcode">
        <label class="vaccineform__label vaccineform__label-required" for="age">Age</label>
        <input class="vaccineform__input" type="number" id="age">
        <label class="vaccineform__label vaccineform__label-required" for="dob">Date of Birth</label>
        <input class="vaccineform__input" type="date" id="dob">
        <label class="vaccineform__label vaccineform__label-required" for="gender">Gender</label>
        <select class="vaccineform__select" id="gender" name="gender">
          <option value="Male">Male</option>
          <option value="Female">Female</option>
          <option value="other">Other</option>
        </select>
        <h3 class="intropage__title">Primay Language</h3>
        <label class="vaccineform__label vaccineform__label-required" for="Language">Language</label>
        <select class="vaccineform__select" id="language" name="language">
          <option value="language 1">language 1</option>
          <option value="language 2">language 2</option>
          <option value="language 3">language 3</option>
        </select>
        <h3 class="intropage__title">Ethnicity</h3>
        <label class="vaccineform__label vaccineform__label-required" for="Ethnicity">Ethnicity</label>
        <select class="vaccineform__select" id="language" name="language">
          <option value="Ethnicity">Ethnicity</option>
          <option value="Ethnicity">Ethnicity</option>
          <option value="Ethnicity">Ethnicity</option>
        </select>
        <h3 class="intropage__title">Race</h3>
        <label class="vaccineform__label vaccineform__label-required" for="Race">Race</label>
        <select class="vaccineform__select" id="language" name="language">
          <option value="Race">Race</option>
          <option value="Race">Race</option>
          <option value="Race">Race</option>
        </select>
        <h3 class="intropage__title">Emergency Contact</h3>
        <label class="vaccineform__label vaccineform__label-required" for="EmergencyContactname">Emergency Contact Name</label>
        <input class="vaccineform__input" type="text" id="EmergencyContactname">
        <label class="vaccineform__label vaccineform__label-required" for="EmergencyContactPhone">Emergency Contact Phone</label>
        <input class="vaccineform__input" type="number" id="EmergencyContactPhone">
      </form>
      <a class="intropage__button" type="button" href="/form2">CONTINUE</a>
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

.vaccineform{
  text-align: left;
}
.vaccineform__label{
  display: block;
  font-size: 18px;
  line-height: 150%;
  margin-bottom: 16px;
}
.vaccineform__label-required::after {
  color: #f55753;
  content: ' *';
}
.vaccineform__input {
  background: #F9F9F9;
  border: 1px solid #E0E0E0;
  box-sizing: border-box;
  border-radius: 8px;
  height: 70px;
  margin-bottom: 40px;
  width: 100%;
  padding: 0 20px;
}
.vaccineform__select {
  -webkit-appearance: none;
  -moz-appearance: none;
  -ms-appearance: none;
  appearance: none;
  outline: 0;
  box-shadow: none;
  background: #F9F9F9;
  border: 1px solid #E0E0E0;
  box-sizing: border-box;
  border-radius: 8px;
  height: 70px;
  margin-bottom: 40px;
  width: 100%;
  padding: 0 20px;
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
