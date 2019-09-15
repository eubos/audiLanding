<template>
<div class="container banner">
  <div class="row align-items-center m-0 banner">
  <div class="row align-items-center border2 p-5">
    <div class="col-lg-5">
      <img src="../assets/images/audi.png" alt="">
    </div>
    <div class="col-lg-7 pl-4">
      <div class="row align-items-center">
          <div class="col-sm-6 bold fsM text-nowrap striped-drop-shadow">
              2019 Q5
          </div>
          <div class="col-sm-6">
              <div class="font-bold lh13">
              2.OT Quattro <br> Premium
              </div>
          </div>
      </div>
      <br>
      <div class="row">
          <div class="col-md-6 lh1">
              <div class="red bold fs07 text-uppercase mb-0">Everyone Qualifies</div>
              <div class="bold fs09">$ <strong class="fs3">499</strong> 39 Mo. Lease</div>
              <small class="fs07 text-nowrap">$3,500 Due at Signing | $0 Security Deposit</small> 
          </div>
          
          <div class="col-md-6 lh1">
              <br class="d-md-none">
              <div class="red bold fs07 text-uppercase mb-0">Current Audi Owners</div>
              <div class="bold fs09">$ <strong class="fs3">479</strong> Mo. Lease </div>
              <small class="fs07 text-nowrap">$3,500 Due at Signing</small> 
          </div>
      </div>
      <br>
      <hr class="d-none d-md-block d-xl-block">
      <br>
      <div class="row">
          <div class="col fs07">
            MSRP: $47,450. 10K mi/yr. lease excludes tax, title, and plate free. For qualified customers though
            Audi Financial Services. Vehicle image shown for illustrative purposes only. #WC2776. Offer ends 09/03/19.
          </div>
      </div>
    </div>
  </div>
  </div>
 </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
  .banner{
    width: 100%;
    height: 100vh;
  }
  .striped-drop-shadow {
  position: relative;
	font-size: 6em;
	background: rgba(0, 0, 0, 0);
	background-size: 14px 14px;
	background-image: repeating-linear-gradient(135deg, rgba(247, 212, 212, 1), rgba(247, 212, 212, 1) 2px, transparent 1px, transparent 5px);
  -webkit-background-clip: text;
  background-clip: text;
	-webkit-text-fill-color: transparent;
}
.striped-drop-shadow:before {
	content: '2019 Q5';
	text-shadow: 3px 3px #ff3333;
	position: absolute;
	top: -7px;
	left: 7px;
}

@media screen and (min-width: 992px) {
    img{
    width: 150%;
    right: 55%;
    position: relative;
  }
    .border2{
    border: 3px solid #ddd;
    position: relative;
    left: 10% !important;
  }
    .fsM{
    font-size: 3em;
  }
}
@media screen and (max-width: 992px) {
    img{
    width: 100%;
    top: -7rem;
    margin-bottom: -7rem;
    position: relative;
  }
    .border2{
    border: 3px solid #ddd;
    position: relative;
  }
    .fsM{
    font-size: 2.5em;
  }
}
</style>