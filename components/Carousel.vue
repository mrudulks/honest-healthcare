<template>
    <div class="carousel">
        <slot></slot>
        <button class="btn next" type="button" @click="next">
            <svg style="width:24px;height:24px;" viewBox="0 0 24 24">
                <path fill="currentColor" d="M22,12A10,10 0 0,1 12,22A10,10 0 0,1 2,12A10,10 0 0,1 12,2A10,10 0 0,1 22,12M20,12A8,8 0 0,0 12,4A8,8 0 0,0 4,12A8,8 0 0,0 12,20A8,8 0 0,0 20,12M8.6,16.6L13.2,12L8.6,7.4L10,6L16,12L10,18L8.6,16.6Z" />
            </svg>
        </button>
        <button class="btn prev" type="button" @click="prev">
            <svg style="width:24px;height:24px" viewBox="0 0 24 24">
                <path fill="currentColor" d="M22,12A10,10 0 0,1 12,22A10,10 0 0,1 2,12A10,10 0 0,1 12,2A10,10 0 0,1 22,12M20,12A8,8 0 0,0 12,4A8,8 0 0,0 4,12A8,8 0 0,0 12,20A8,8 0 0,0 20,12M15.4,16.6L10.8,12L15.4,7.4L14,6L8,12L14,18L15.4,16.6Z" />
            </svg>
        </button>
    </div>
</template>
<script>
export default{
    data(){
        return{

        }
    },
    methods:{
        next(){
            this.$emit('next')
        },
        prev(){
            this.$emit('prev')
        }
    }
}
</script>
<style>
.carousel{
    overflow: hidden;
    position: relative;
    margin: auto;
    height: 250px;
    width: 300px;
}
button{
    color: gray;
}
.carousel .next{
    position: absolute;
    bottom: 0;
    right: 40%;
    padding: 0;
    border: 0;
}
.carousel .prev{
    position: absolute;
    bottom: 0;
    left: 40%;
    padding: 0;
    border: 0;
}
@media only screen and (min-width: 480px) {
    .carousel{
        min-height: 200px;
        width: 400px;
    }
}
@media only screen and (min-width: 600px) {
.carousel{
    min-height: 150px;
    width: 600px;
}
}
</style>