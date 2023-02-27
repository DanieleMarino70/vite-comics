<script>

export default {
    data() {
        return {
        }
    },

};
</script>

<template>

    <footer>
        <div class="footer-upper">
            <div class="container">
                <nav>

                </nav>

                <div class="img-container">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>

        <div class="footer-bottom">
            <div class="container">

            </div>
        </div>
    </footer>

</template>

<style lang="scss" scoped>

.footer-upper{
    background-image: url("../assets/img/footer-bg.jpg");
    background-repeat:repeat-x;
    max-height: 400px;

    .container{
        display: flex;
        justify-content: space-between;
        

        .img-container{
                height: 447px;
                position: relative;
                overflow: hidden;
                bottom: 47px;
            img{
                max-width: 100%;
                height: auto;
                object-fit: cover;
                object-position: top;
            }
        }
    }


}

</style>
