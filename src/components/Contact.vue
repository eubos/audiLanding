<template>
        <div class="container-fluid m-0 p-0 contact">
            <div class="row align-items-center m-0 contact">
                <div class="col-lg-1">
                </div>
                <div class="col-lg-3 font-weight-light lh13 d-none d-lg-block d-xl-block pr-4">
                   <p class="text-uppercase">Contact info</p> 
                   <p class="fs12">We appreciate your interest in our inventory, and apologize we do not have model details displaying on the website at this time.</p>
                   <p class="fs12">Please fill the form out below and our team will quickly respond, or, please call us at 765-470-4091 for more information.</p>
                <br>
                <form action="#" class="simple-form ">
                  <div class="input-group">
                  <input type="text" class="form-control" placeholder="   First name*" aria-label="First Name*" required>
                  </div>
                  <br>
                  <div class="input-group">
                  <input type="text" class="form-control" placeholder="   Last name*" aria-label="Last Name*" required>
                  </div>
                  <br>
                  <div class="input-group">
                  <input type="text" class="form-control" placeholder="   E-mail*" aria-label="E-mail*" required>
                  </div>
                  <br>
                  <div class="input-group">
                  <input type="text" class="form-control" placeholder="   Phone" aria-label="Phone">
                  </div>
                  <div class="row align-items-center">
                    <div class="col">
                      <label class="pt-4 pb-3">
                        <input type="radio" class="form-radio" name="dva"/> Prefer e-mail
                      </label> 
                  </div>
                  <div class="col">
                      <label class="pt-4 pb-3">
                        <input type="radio" class="form-radio" checked name="dva"/> Prefer phone
                      </label>
                  </div>
                  </div>
                  <button type="button" class="text-white bold">CONTACT US</button>
                </form>
                </div>
                <div class="col-lg-8 pt-5 pl-5 pr-5 pb-5 right-block">
                  <div class="row">
                    <div class="col-md text-white pt-5"><h2>CAN'T FIND WHAT YOU LOOKING FOR?</h2></div>
                  </div>
                  <div class="row">
                    <div class="col-lg-6 pt-3">
                      <select class="custom-select form-control">
                      <option disabled selected>Any type (New and Pre-owned)*</option>
                      <option value="1">New</option>
                      <option value="2">Pre-owned</option>
                      </select>
                    </div>
                    <div class="col-sm pt-3">
                      <select class="custom-select form-control">
                      <option disabled selected>From 1999*</option>
                      <option value="1">2000</option>
                      <option value="2">2001</option>
                    </select>
                    </div>
                    <div class="text-white pl-1 pt-4 d-none d-lg-block">—</div>
                    <div class="col-sm pt-3">
                      <select class="custom-select form-control">
                      <option disabled selected>To 2019*</option>
                      <option value="1">2018</option>
                      <option value="2">2017</option>
                    </select>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-md-6 pt-3">
                      <select class="custom-select form-control">
                      <option value="1" selected>Audi*</option>
                      <option value="2">Nissan</option>
                      <option value="3">Volkswagen</option>
                      <option value="4">Mitsubishi</option>
                      </select>
                    </div>
                    <div class="col-md-6 pt-3">
                      <select class="custom-select form-control">
                      <option value="1" selected>Q5*</option>
                      <option value="2">Q3</option>
                      <option value="3">Q7</option>
                      </select>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-md-6 pt-3">
                       <select class="custom-select form-control">
                      <option disabled selected>Price (max)*</option>
                      <option value="1">50.000</option>
                      <option value="2">30.000</option>
                      <option value="3">20.000</option>
                      </select>
                    </div>
                     <div class="col-md pt-3">
                      <select class="custom-select form-control">
                      <option disabled selected>Trim*</option>
                    </select>
                    </div>
                    <div class="col-md pt-3">
                      <select class="custom-select form-control">
                      <option disabled selected>Color*</option>
                      <option value="1">Black</option>
                      <option value="2">White</option>
                    </select>
                    </div>
                  </div>
                  <div class="row pt-3">
                    <div class="col">
                      <input type="text" class="form-control" placeholder="   Your message" aria-label="message" >
                    </div>
                  </div>
                  <div class="row pt-3">
                    <div class="col">
                      <p class="text-white font-weight-light" style=" ">By submitting this form, you agree to be contacted with information regarding the vehicle you are searching for.</p>
                    </div>
                  </div>
                  <div class="row pt-4">
                    <div class="col-md-4">
                      <button type="button" class="text-white bold">LET US FIND IT</button>
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
.contact{
  width: 100%;
  height: 100vh;
}

.form-control{
  margin: 0 .25rem;
  border: 1px solid;
  border-radius: 40px;
  transition: border-color .5s ease-out;
  background-color: #f3f6fc;
  border-color: #e5eaf3;
  font-size: .9em;
  height: 3.5em;
}

button{
  margin: 0 .25rem;
  border: 0px solid;
  border-radius: 40px;
  transition: border-color .5s ease-out;
  background-color: #000;
  border-color: #e5eaf3;
  font-size: .7em;
  height: 4.5em;
  width: 60%;
  box-shadow: 5px 5px 0px 0px rgba(0, 0, 0, 0.205); 
}
.form-radio
{
     -webkit-appearance: none;
     -moz-appearance: none;
     appearance: none;
     display: inline-block;
     position: relative;
     background-color: #fff;
     color: #666;
     top: 2px;
     height: 1em;
     width: 1em;
     border: 1.5px solid #ff3333;
     border-radius: 50px;
     cursor: pointer;     
     outline: none;
}

.form-radio:checked
{
     background-color: #ff3333;
}

label
{
    color: #333;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    cursor: pointer;
    font-size: .9em;

}
 
.right-block{
  background-image: url(../assets/images/contact-background.png);
  background-repeat: no-repeat;
  background-position: right bottom;
}

@media screen and (min-width: 992px) {
.right-block{
  height: 90%;
}
}
@media screen and (max-width: 992px) {
.right-block{
  height: auto;
  background-size: auto 100%;
}
.pl-5 {
  padding-left: 3% !important;
}
.pr-5{
  padding-right: 3% !important
}
}
</style>