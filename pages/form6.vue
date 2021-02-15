<template>
  <div class="container">
    <div class="container__width">
      <Logo />
      <div class="ticket">
        <div class="ticket__status ticket__status-pending">
          <img src="../assets/pending.svg" alt="pending">
        </div>
        <div class="ticket__status-ticketid">TICKET ID</div>
        <div class="ticket__status-ticketidnumber">#ZED1291</div>
      </div>
      <h3 class="ticket__heading">General Instructions</h3>
      <ul class="ticket__ul">
        <li class="ticket__li">I have been given a copy and have read, or have had explained to me, the information in the FACT SHEET for the COVID-19vaccine.</li>
        <li class="ticket__li">I understand the FDA has authorized emergency use of the COVID-19 vaccine, which is not an FDA-approved vaccine. Ihave had the chance to ask questions that were answered to my satisfaction.</li>
        <li class="ticket__li">I understand the COVID-19 vaccine requires 2 doses given 4 weeks apart. If this is my first dose of the COVID-19 vaccine, Iintend to receive a second dose of the same vaccine in accordance with the timeframe specified in the FACT SHEET to completethevaccination series.I consent to receive call and/or text message reminders at the mobile phone number provided above.</li>
        <li class="ticket__li">My signature acknowledges that I was advised to remain on site for 15 minutes after receiving the vaccine. Those with ahistory of previous anaphylactic reactions, should stay on site for 30 minutes.  I understand that if I experience any adversereaction, it will be my responsibility to follow up with my primary care physician.</li>
        <li class="ticket__li">An administration fee may be billed to third party payers. I authorize Compass/Lanoi Medical Group to bill any and all third partypayers for this service.  I authorize the release of any medical or other information necessary to process this claim. I also requestpayment of government benefits or payment of medical benefits either to myself or to the party who accepts assignment for ser vicesdescribed herein.</li>
        <li class="ticket__li">I ALLOW my/my child’s immunization record to be shared with other health care providers, agencies, or schools in the CaliforniaImmunization Registry</li>
        <li class="ticket__li">I understand the significant known and potential risks and benefits of the COVID-19 vaccine as explained in the FACT SHEET andthat some potential risks and benefits may remain unknown. I REQUEST THE COVID-19 VACCINE BE GIVEN TO ME ORTHE PERSON LISTED ABOVE</li>
      </ul>
      <a class="intropage__button" type="button" href="/form7">DOWNLOAD TICKET</a>
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
.ticket{
  background: #F9F9F9;
  padding: 40px;
  padding-top: 60px;
  margin-bottom: 70px;
}
.ticket__status{
  height: 150px;
  width: 150px;
  color: #fff;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: auto;
}
.ticket__status-pending{
  background: #F7E35E;
}

.ticket__status-ticketid {
  margin-top: 70px;
  font-weight: bold;
  font-size: 18px;
  line-height: 150%;
  letter-spacing: 0.04em;
  margin-bottom: 18px;
  color: #333333
}
.ticket__status-ticketidnumber{
  font-weight: bold;
  font-size: 36px;
  line-height: 150%;
  letter-spacing: 0.04em;
}
.ticket__heading{
  text-align: left;
  font-weight: 600;
  font-size: 24px;
  line-height: 29px;
  margin-bottom: 50px;
}
.ticket__ul{
  padding-left: 18px;
}
.ticket__li{
  text-align: left;
  padding-bottom: 40px;
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
