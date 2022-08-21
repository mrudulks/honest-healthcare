<template>
  <nav class="honor-navbar" :class="{ scrolled : scrollUp }" >
    <div class="honor-nav-contents container">
      <div class="honor-logo">
        <img src="./../assets/img/honor-logo.png" alt="">
      </div>
      <div class="honor-nav">
        <ul class="honor-nav-items">
          <li>
            <nuxt-link to="/">Home</nuxt-link>
          </li>
          <li>
            <nuxt-link to="#about">about</nuxt-link>
          </li>
          <li>
            <nuxt-link to="#service">service</nuxt-link>
          </li>
          <li>
            <nuxt-link to="#contact">contact us</nuxt-link>
          </li>
          
        </ul>
      </div>
    </div>
  </nav>
</template>
<script>
export default {
    data(){
        return{
            scrollUp:false,
            windowTop:0
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
.honor-navbar{
    padding: 1rem 0;
    position: fixed;
    width: 100%;
    background: transparent;
    transition: .3s ease-in;
}
.honor-navbar.scrolled{
    padding: 0 0;
        background: rgb(34 94 130 / 84%);
}
.honor-nav-contents{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.honor-logo img{
    width: 120px;
}
.honor-nav-contents .honor-nav-items{
    display: flex;
    align-items: center;
    margin: 0;
}
.honor-nav-contents .honor-nav-items li a{
        padding: 1rem;
        display: block;
        text-transform: uppercase;
        color: #fff;
        font-size: 14px;
}
.honor-nav-contents .nuxt-link-exact-active.nuxt-link-active{
    background: #398a6d;
    color: #fff;
}
</style>
