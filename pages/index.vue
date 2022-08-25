<template>
<div class="main-div">
   <section id="banner" class="banner">
    <div class="bg-color">
    
      <div class="container">
        <div class="row">
          <div class="banner-info">
            <div class="banner-logo text-center mb-3">
              <img src="@/assets/img/honor-logo.png" class="img-responsive">
            </div>
            <div class="banner-text text-center">
              <h1 class="white">Healthcare at your desk!!</h1>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod <br>tempor incididunt ut labore et dolore magna aliqua.</p>
              <a href="#contact" class="btn btn-appoint">Make an Appointment.</a>
            </div>
            <div class="overlay-detail text-center">
              <a href="#service"><i class="fa fa-angle-down"></i></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!--/ banner-->
    <!--about-->
  <section id="about" class="section-padding">
    <div class="container">
      <div class="row">
        <div class="col-lg-3 col-xs-12 mb-5">
          <div class="section-title">
            <h2 class="head-title lg-line">About Us</h2>
            <hr class="botm-line">
            <p class="sec-para text-justify-sm">Nursing Employment Agency that places Registered Nurses, Registered Practical Nurses and Personal Support Workers in hospitals, Long-term Care facilities and Home Care settings in Ontario.</p>
            <a href="" style="color: #0cb8b6; padding-top:10px;">Know more..</a>
          </div>
        </div>
        <div class="col-lg-9  col-xs-12">
          <div style="visibility: visible;" class="col-md-9 more-features-box">
            <div class="more-features-box-text">
              <div class="more-features-box-text-icon"> <i class="fa fa-angle-right" aria-hidden="true"></i> </div>
              <div class="more-features-box-text-description">
                <h4>Honest Healthcare</h4>
                <p class="text-justify-sm">Honest Healthcare Staffing Solutions was established by a group of people working in the Health Care Industry who are passionate about making a difference in people’s lives by providing quality care and support. HONEST HEALTHCARE is managed by health care professionals with many years of experience in hospital, community and Long-term Care settings. Our team includes Registered Nurses, Registered Practical Nurses, Personal Support Workers, RSWs/HCAs and experienced managers. This diversity helps us to understand your needs and your requirements when you request a service from us.</p>
              </div>
            </div>
            <div class="more-features-box-text">
              <div class="more-features-box-text-icon"> <i class="fa fa-angle-right" aria-hidden="true"></i> </div>
              <div class="more-features-box-text-description">
                <h4>It's something important you want to know.</h4>
                <p class="text-justify-sm">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et. Ut wisi enim ad minim veniam, quis nostrud.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-12 text-center pt-5">
          <h2 class="ser-title">What We Do</h2>
          <hr class="botm-line botm-line-center text-center">
          <p class="px-5p text-justify-sm">We act as a middleman between employers and professional workers, helping to match qualified professionals for your facility.
If you are an employer, contact us and we will take care of your need in a professional manner.
If you are an employee, send us your resume with cover letter and references, we will contact you </p>
        </div>
      </div>
    </div>
  </section>
  <!--/ about-->
  <!--service-->
  <section id="service" class="section-padding">
    <div class="container">
      <div class="row">
        <div class="col-lg-4 col-md-12 mb-5">
          <h2 class="ser-title">Our Service</h2>
          <hr class="botm-line">
          <p class="text-justify-sm">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris cillum.</p>
          
        </div>
        <div class="col-lg-8 col-sm-12 ">
        <div class="row">
           <div class="col-md-4 mb-4">
           <div class="service-info">
            <div class="icon">
              <i class="fa fa-stethoscope"></i>
            </div>
            <div class="icon-info">
              <h4>Nursing Services(RN & RPN)</h4>
              <p>Our Registered Staff, licensed with CNO provide quality care as part of an interdisciplinary </p>
            </div>
            <nuxt-link to="/services" class="btn btn-form mt-auto">Read More <i class="ms-2 fa fa-arrow-right"></i></nuxt-link>
          </div>
        </div>

        <div class="col-md-4 mb-4">
         <div class="service-info">
            <div class="icon">
              <i class="fa fa-ambulance"></i>
            </div>
            <div class="icon-info">
              <h4>Personal Support Workers</h4>
              <p>Our staff are graduates of a recognized Personal Support Worker program, demonstrate focus</p>
            </div>
            <a class="btn btn-form mt-auto" href="#">Read More  <i class="ms-2 fa fa-arrow-right"></i></a>
          </div>
        </div>

        <div class="col-md-4 mb-4">
         <div class="service-info">
            <div class="icon">
              <i class="fa fa-user-md"></i>
            </div>
            <div class="icon-info">
              <h4>Home Health Care</h4>
              <p>Honest Healthcare offers homecare for your loved ones as well as post-operative care. </p>
            </div>
            <a class="btn btn-form mt-auto" href="#">Read More  <i class="ms-2 fa fa-arrow-right"></i></a>
          </div>
        </div>
        </div>
        </div>
      </div>
    </div>
  </section>
  <!--/ service-->
  <!--cta-->  
  
  </div>
  <!--/ contact-->
  
</template>

<script>
import VHeader from '~/components/VHeader.vue';
export default {
  name: 'IndexPage',
  components:{
    VHeader
  }
}
</script>
