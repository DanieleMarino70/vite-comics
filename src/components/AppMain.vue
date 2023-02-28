<script>
import cardMain from './cardMain.vue'
export default {
    data() {
        return {
        }
    },
    props:{
        comics: Array,
    },
    components:{cardMain}

};
</script>

<template>
    <main>
        <div class="jumbotron">
            <div class="container">
                <div class="row">
                    <cardMain v-for="comic in comics" :comic="comic" />
                </div>
            </div>
        </div>

    
    </main>
</template>

<style lang="scss" scoped>
main{
    background-color: rgb(50,50,50);
    // debug




.jumbotron{
    .container{
        
        .row{
            display: flex;
            flex-wrap: wrap;
            padding: 10px;
        }
    }
}

}
</style>
