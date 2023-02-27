<script>
export default {
    data() {
        return {
            headerLinks: [
                {
                    title: "Characters",
                    url: "#"
                },
                {
                    title: "Comics",
                    url: "#"
                },
                {
                    title: "Movies",
                    url: "#"
                },
                {
                    title: "Tv",
                    url: "#"
                },
                {
                    title: "Games",
                    url: "#"
                },
                {
                    title: "Collectibles",
                    url: "#"
                },
                {
                    title: "Videos",
                    url: "#"
                },
                {
                    title: "Fans",
                    url: "#"
                },
                {
                    title: "News",
                    url: "#"
                },
                {
                    title: "Shop",
                    url: "#"
                },
            ]
        }
    },
    
};
</script>

<template>
  <header>
    <div class="container">
        <img src="../assets/img/dc-logo.png" alt="">
        <ul>
            <li v-for="link in headerLinks"><a :href="link.url">{{ link.title }}</a></li>
        </ul>
    </div>
  </header>
</template>

<style lang="scss" scoped>
header{
    background-color: wheat;

    .container{
        display: flex;
        justify-content: space-between;

        img{
            height: 80px;
            align-self: center;
            max-width: 100%;
        }
    
        ul {
            display: flex;
            list-style: none;
            line-height: 6rem;

            li{
                text-decoration: none;
                margin: 0 10px;

                a{
                    color: inherit;
                    text-decoration: none;
                }
            }
        }


    }
}
</style>
