<script>
export default {
    data() {
        return {
        }
    },
    props:{
        comic: Object,
    }

};
</script>

<template>
    
    <div class="col" :comic="comic">
        <div class="img-container">
            <img :src="comic.thumb" alt="">
        </div>
        <h2>{{ comic.series }}</h2>
    </div>
      
</template>

<style lang="scss" scoped>
    .col{
        width: calc(100% / 6 - 20px);
        text-align: center;
        
        .img-container{
            display: inline-block;
            width:150px;
            height: 150px;
            img{
                width: 100%;
                height: 100%;
                object-fit: cover;
        
            }
        }

        h2{
            font-size: 0.8rem;
            color: white;
        }
    }

</style>