<template>
  <div id="myPage" data-spy="scroll" data-target=".navbar" data-offset="60">
    <v-header :innerPage='innerPage'></v-header>
    <Nuxt />
    <!--footer-->
    <v-footer></v-footer>
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
