<template>
  <div class="main-container">
    <section class="subpage-banner">
      <h2>Contact Us</h2>
    </section>
    <!--contact-->
    <section id="contact" class="section-padding">
      <div class="container">
        <div class="row">
          <!-- <div class="col-md-12">
          <h2 class="ser-title">Contact us</h2>
          <hr class="botm-line">
        </div> -->
          <div class="col-md-4 col-sm-12 mb-5">
            <h3>Contact Info</h3>
            <div class="space"></div>
            <p><i class="fa fa-user fa-fw pull-left fa-2x"></i>Sanal Kumar C S </p>
            <div class="space"></div>
            <p><i class="fa fa-map-marker fa-fw pull-left fa-2x"></i>69 Daventry way , Komoka , <br>NOL1R0 ,ONTARIO321
            </p>
            <div class="space"></div>
            <p><i class="fa fa-envelope-o fa-fw pull-left fa-2x"></i>info@companyname.com</p>
            <div class="space"></div>
            <p><i class="fa fa-phone fa-fw pull-left fa-2x"></i>+1 2265044465, +1 2265040465</p>
          </div>
          <div class="col-md-8 col-sm-12 marb20">
            <div class="contact-info">
              <h3 class="cnt-ttl">Having Any Query! Or Book an appointment</h3>
              <div class="space"></div>
              <div id="sendmessage">Your message has been sent. Thank you!</div>
              <div id="errormessage"></div>
              <form action="" method="post" role="form" class="contactForm">
                <div class="row">
                  <div class="form-group mb-4 col-md-4">
                    <label for="">First Name</label>
                    <input type="text" name="name" class="form-control br-radius-zero" id="name" placeholder="Fore Name"
                      data-rule="minlen:4" data-msg="Please enter at least 4 chars" />
                    <div class="validation"></div>
                  </div>
                  <div class="form-group mb-4 col-md-4">
                    <label for="">Middle Name</label>
                    <input type="text" name="name" class="form-control br-radius-zero" id="name" placeholder="Middele Name"
                      data-rule="minlen:4" data-msg="Please enter at least 4 chars" />
                    <div class="validation"></div>
                  </div>
                  <div class="form-group mb-4 col-md-4">
                    <label for="">Surname</label>
                    <input type="text" name="name" class="form-control br-radius-zero" id="name" placeholder="Surname"
                      data-rule="minlen:4" data-msg="Please enter at least 4 chars" />
                    <div class="validation"></div>
                  </div>
                  <div class="form-group mb-4 col-md-4">
                  <p>Gender</p>
                  <input type="checkbox" name="" id="gender-check1">
                    <label for="gender-check1">Male</label>
                    <input type="checkbox" name="" id="gender-check2">
                    <label for="gender-check2">Female</label>
                    <input type="checkbox" name="" id="gender-check3">
                    <label for="gender-check3">Other</label>
                  </div>
                  <div class="form-group mb-4 col-md-4">
                    <div>
                        <p>Position Applying For?</p>
                        
                        <div class="d-flex flex-column">
                        <div class="form-group mb-2">
                            <input type="checkbox" name="" id="position1">
                        <label for="position1">Registered Nurse (RN)</label>
                        </div>
                        <div class="form-group  mb-2">
                            <input type="checkbox" name="" id="position1">
                        <label for="position1">Registered Practical Nurse (RPN)</label>
                        </div>
                        <div class="form-group  mb-2">
                        <input type="checkbox" name="" id="position1">
                        <label for="position1">Personal Support Worker (PSW)</label>
                        </div>
                        </div>
                    </div>
                  </div>
                  <div class="form-group mb-4 col-md-6">
                    <label for="">Phone Number</label>
                    <input type="text" name="name" class="form-control br-radius-zero" id="name" placeholder="Use Country Code (eg: +1 for Canada)"
                      data-rule="minlen:4" data-msg="Please enter at least 4 chars" />
                  </div>
                  <div class="form-group mb-4 col-md-6">
                    <label for="">Email</label>
                    <input type="text" name="name" class="form-control br-radius-zero" id="name" placeholder="Email"
                      data-rule="minlen:4" data-msg="Please enter at least 4 chars" />
                  </div>

                  <div class="form-group mb-4 col-md-6">
                    <label for="">Address</label>
                    <textarea name="" id="" cols="30" rows="10" placeholder="Present Address" class="form-control br-radius-zero"></textarea>
                  </div>
                  <div class="form-group mb-4 col-md-6">
                    <label for="">Employment History</label>
                    <textarea name="" id="" cols="30" rows="10" placeholder="Please record the details of your full employment history beginning with your current or most recent position held" class="form-control br-radius-zero"></textarea>
                  </div>
                  <div class="form-group mb-4 col-md-6">
                    <label for="">Professional & Educational Qualifications	</label>
                    <textarea name="" id="" cols="30" rows="10" placeholder="Please list all relevant qualifications." class="form-control br-radius-zero"></textarea>
                  </div>
                  <div class="form-group mb-4 col-md-6">
                    <label for="">Supporting Information	</label>
                    <textarea name="" id="" cols="30" rows="10" placeholder="Please include your reasons for applying and take the opportunity to highlight your particular talents and strengths." class="form-control br-radius-zero"></textarea>
                  </div>
                  <div class="form-group mb-4 col-md-6">
                    <label for="">References	</label>
                    <textarea name="" id="" cols="30" rows="10" placeholder="Please provide the names and full contact details of the people who have agreed to supply references" class="form-control br-radius-zero"></textarea>
                  </div>
                  <div class="form-group mb-4 col-md-6">
                    <label for="">How did you hear about us?</label>
                    <textarea name="" id="" cols="30" rows="10" placeholder="Please indicate the name of the person who referred you to us." class="form-control br-radius-zero"></textarea>
                  </div>
                  <div class="form-group mb-4 col-md-6">
                    <label for="">Upload Documents</label>
                    <input type="file" name="" id="">
                   </div>
                </div>

                <div class="form-action">
                  <button type="submit" class="btn btn-form">Send Message</button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- -->
  </div>
</template>
<script>
export default {
  layout:"pages",
  data(){
    return{

    }
  }
}
</script>
<style>
  .subpage-banner {
    min-height: 350px;
    background-image: url("assets/img/contact-banner.jpg");
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .subpage-banner h2 {
    color: #fff;
  }

</style>
