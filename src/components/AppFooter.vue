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
                <ul>
                    <li><a href="" class="button outline-primary">SIGN UP NOW!</a></li>
                </ul>

                <ul>
                    <li><h2>FOLLOW US</h2></li>
                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                    <li><img src="../assets/img/footer-twitter.png" alt=""></li>
                    <li><img src="../assets/img/footer-youtube.png" alt=""></li>
                    <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
                    <li><img src="../assets/img/footer-periscope.png" alt=""></li>
                </ul>
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

.footer-bottom{
    height: 100px;
    background-color: rgb(80,80,80);

    .container{
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 100%;

        ul{
            display: flex;

            li{
                align-self: center;
                margin: 0 10px;

                h2{
                    color: #0282f9;
                }

                .button.outline-primary{
                    color: white;
                    text-decoration: none;
                    
                    padding: 10px;
                    border: 2px solid #0282f9;
                }
            }
        }
    }
}
</style>
