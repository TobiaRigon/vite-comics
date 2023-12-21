<script>


export default {
    name: "AppHeader",
    data() {
        return {
            links: [
                {
                    text: "Home",
                    url: "#",
                    current: false,
                },
                {
                    text: "Comics",
                    url: "#",
                    current: true,
                },
                {
                    text: "Movies",
                    url: "#",
                    current: false,
                },
                {
                    text: "TV",
                    url: "#",
                    current: false,
                },
                {
                    text: "Games",
                    url: "#",
                    current: false,
                },
                {
                    text: "Collectibles",
                    url: "#",
                    current: false,
                },
                {
                    text: "Video",
                    url: "#",
                    current: false,
                },
                {
                    text: "Fans",
                    url: "#",
                    current: false,
                },
                {
                    text: "News",
                    url: "#",
                    current: false,
                },
                {
                    text: "Shop",
                    url: "#",
                    current: false,
                },

            ]
        }
    }
}


</script>

<template>
    <header>
        <div class="container">
            <img src="../assets/img/dc-logo.png" alt="dc-logo">
            <div class="menu">
                <nav>
                    <ul>
                        <li v-for="link in links" :class="link.current ? 'active' : ''">
                            <a :href="link.url">
                                {{ link.text }}</a>
                        </li>

                    </ul>
                </nav>
            </div>
        </div>

    </header>
</template>

<style scoped lang="scss">
@import "../style/partial/variables.scss";


.container {
    background-color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;

    img {
        padding: 15px 0;
    }

    .menu {
        display: inline-block;
        text-align: end;

        ul {
            display: flex;
            gap: 20px;
            list-style-type: none;



            li {
                padding: 55px 0;



                a {
                    text-decoration: none;
                    text-transform: uppercase;
                    font-weight: 600;
                    color: #707070;
                }

                &:hover {
                    border-bottom: 3px solid $main_blue;
                }
            }

            .active {
                border-bottom: 3px solid $main_blue;
            }


        }
    }
}
</style>
