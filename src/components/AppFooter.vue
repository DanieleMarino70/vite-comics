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
                    <ul>
                        <li><h2>DC COMICS</h2></li>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>

                    <ul>
                        <li><h2>SHOP</h2></li>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>

                    <ul>
                        <li><h2>DC</h2></li>
                        <li>Terms Of Use</li>
                        <li>Privacy policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact us</li>
                    </ul>

                    <ul>
                        <li><h2>SITES</h2></li>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
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
    height: 400px;

    

    .container{
        display: flex;
        justify-content: space-between;
        height: 100%;
        

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

    nav{
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;

        ul{
            margin: 10px 10px;
            li{
                color: grey;
                margin: 5px 0;
                h2{
                    margin: 8px 0;
                    color:white;
                }
            }
        }
    }


}

</style>
