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
        <img :src="comic.thumb" alt="">
        <h2>{{ comic.series }}</h2>
    </div>
      
</template>

<style lang="scss" scoped>
    .col{
        padding: 5px;
        width: calc(100% / 6);
        min-height: 100px;
        
        img{
            width: 100%;
            height: 150px;
            object-fit: cover;
        
            
        }

        h2{
            font-size: 0.8rem;
            color: white;
        }
    }

</style>