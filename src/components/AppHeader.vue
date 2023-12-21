<script>


export default {
    name: "AppHeader",
}
</script>

<template>
    <header>
        <div class="container">
            <img src="../assets/img/dc-logo.png" alt="dc-logo">
            <div class="menu">
                <nav>
                    <ul>
                        <li>
                            <a href="">
                                characters
                            </a>
                        </li>

                        <li class="active">
                            <a href="">
                                comics
                            </a>
                        </li>


                        <li>
                            <a href="">
                                movies
                            </a>
                        </li>

                        <li>
                            <a href="">
                                tv
                            </a>
                        </li>

                        <li>
                            <a href="">
                                games
                            </a>
                        </li>

                        <li>
                            <a href="">
                                collections
                            </a>
                        </li>

                        <li>
                            <a href="">
                                videos
                            </a>
                        </li>

                        <li>
                            <a href="">
                                fans
                            </a>
                        </li>

                        <li>
                            <a href="">
                                news
                            </a>
                        </li>

                        <li>
                            <a href="">
                                shop
                            </a>
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
            }

            .active {
                border-bottom: 3px solid $main_blue;
            }


        }
    }
}
</style>
