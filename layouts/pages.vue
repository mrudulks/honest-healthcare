<template>
  <div id="myPage" data-spy="scroll" data-target=".navbar" data-offset="60">
    <v-header :innerPage='innerPage'></v-header>
    <Nuxt />
    <!--footer-->
    <footer id="footer">
      <div class="top-footer">
        <div class="container">
          <div class="row">
            <div class="col-md-3 col-sm-3 marb20">
              <div class="ftr-tle">
                <h4 class="white no-padding">About Us</h4>
              </div>
              <div class="info-sec">
                <p>Praesent convallis tortor et enim laoreet, vel consectetur purus latoque penatibus et dis parturient.
                </p>
              </div>
            </div>
            <div class="col-md-3 col-sm-3 marb20">
              <div class="ftr-tle">
                <h4 class="white no-padding">Quick Links</h4>
              </div>
              <div class="info-sec">
                <ul class="quick-info">
                  <li><a href="index.html"><i class="fa fa-circle"></i>Home</a></li>
                  <li><a href="#about"><i class="fa fa-circle"></i>About</a></li>
                  <li><a href="#service"><i class="fa fa-circle"></i>Service</a></li>
                </ul>
              </div>
            </div>
            <div class="col-md-3 col-sm-3 marb20">
              <div class="ftr-tle">
                <h4 class="white no-padding">Follow us</h4>
              </div>
              <div class="info-sec">
                <ul class="social-icon">
                  <li class="bglight-blue"><i class="fa fa-facebook"></i></li>
                  <li class="bgred"><i class="fa fa-google-plus"></i></li>
                  <li class="bgdark-blue"><i class="fa fa-linkedin"></i></li>
                  <li class="bglight-blue"><i class="fa fa-twitter"></i></li>
                </ul>
              </div>
            </div>
            <div class="align-items-center col-md-3 d-flex marb20">
              <img src="./../assets/img/honor-logo.png" alt="" class="img-fluid">
            </div>
          </div>
        </div>
      </div>
      <div class="footer-line">
        <div class="container">
          <div class="row">
            <div class="col-md-12 text-center">
              © Copyright
              <!-- <div class="credits">
              Designed by <a href="">BootstrapMade.com</a>
            </div> -->
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
    data(){
        return{
            innerPage:true
        }
    }
}
</script>
