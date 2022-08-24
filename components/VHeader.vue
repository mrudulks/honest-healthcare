<template>
  <nav class="honor-navbar" :class="{ scrolled : scrollUp,inneractive:innerPage }">
    <div class="honor-nav-contents container">
      <div class="honor-logo">
        <img src="./../assets/img/honor-logo.png" alt="">
      </div>
      <div class="honor-nav" :class="{ active : mobBarActive}">
        <button class="btn-close-new" @click="close()">
            <i class="fa fa-close"></i>
        </button>
        <ul class="honor-nav-items">
          <li>
            <nuxt-link to="/">Home</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/#about">about</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/#service">service</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/contact-us">contact us</nuxt-link>
          </li>
          
        </ul>
      </div>
      <button class="btn btn-open" @click="open()">
        <span></span>
        <span></span>
        <span></span>
      </button>
    </div>
  </nav>
</template>
<script>
export default {
    props:['innerPage'],
    data(){
        return{
            scrollUp:false,
            windowTop:0,
            mobBarActive:false
        }
    },
    methods:{
        onScroll(e) {
            this.windowTop = e.target.documentElement.scrollTop;
            if( this.windowTop > 100){
                this.scrollUp = true;
            }
            else{
                this.scrollUp = false;
            }
        },
        open(){
            this.mobBarActive = true;
        },
        close(){
            this.mobBarActive = false;
        }
    },
  mounted() {
    window.addEventListener("scroll", this.onScroll);
  },
  beforeDestroy() {
    window.removeEventListener("scroll", this.onScroll);
  },
  computed:{
    pageOffSet(){
        console.log(window.pageYOffset)
    }
  }
}
</script>
<style>

</style>
