<script>
export default {
    data() {
        return {
            blueLinks:[
                {
                    title: "Digital Comics",
                    url: "#",
                    src:  "/buy-comics-digital-comics.png"
                },
                {
                    title: "Dc Merchandise",
                    url: "#",
                    src: "/buy-comics-merchandise.png"
                },
                {
                    title: "Subscription",
                    url: "#",
                    src: "/buy-comics-subscriptions.png"
                },
                {
                    title: "Comic Shop Locator",
                    url: "#",
                    src: "/buy-comics-shop-locator.png"
                },
                {
                    title: "Dc Power Visa",
                    url: "#",
                    src: "/buy-dc-power-visa.svg"
                },

            ]
        }
    },

};
</script>

<template>
    <div class="background">
        <div class="container">
            <ul>
                <li v-for="link in blueLinks">
                    <div class="img-container">
                        <img :src="link.src" alt="">
                    </div>
                    <a :href="link.url">{{ link.title.toLocaleUpperCase() }}</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.background{
    position: relative;
    z-index: 1;
    background-color: #0282f9;
    .container{
        ul{
            display: flex;
            justify-content: center;
            line-height: 100px;
            color: white;
    
            li{
                display: flex;
                margin: 0 10px;

                a{
                    color: inherit;
                    text-decoration: none;
                    font-size: 0.8rem;
                }

                .img-container{
                    margin: 0 10px;
                    width: 50px;
                    height: 50px;
                    align-self: center;
                    img{
                        display: block;
                        width: 100%;
                        height: 100%;
                        object-fit: contain;
                    }
                }

            }
        }
    }
}
</style>
