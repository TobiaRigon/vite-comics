<script>
export default {
    name: "AppFooter",
}
</script>

<template>
    <footer>

        <section id="top_section">
            <div class="container">
                <a class="cell">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="digital comics icon">
                    <span>digital comics</span>
                </a>
                <a class="cell">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="digital comics icon">
                    <span>dc merchandise</span>
                </a>
                <a class="cell">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="digital comics icon">
                    <span>subscription</span>
                </a>
                <a class="cell">
                    <img src="..\assets\img\buy-comics-shop-locator.png" alt="digital comics icon">
                    <span>comic shop locator</span>
                </a>
                <a class="cell">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="digital comics icon">
                    <span>dc power visa</span>
                </a>
            </div>
        </section>

        <section id="mid_section">
            <div class="container">

            </div>
        </section>
        <section id="bottom_section">
            <div class="container">

            </div>
        </section>

    </footer>
</template>

<style scoped lang="scss">
@import "../style/partial/_variables.scss";

#top_section {
    background-color: $main_blue;
    min-height: 30px;

    .container {
        display: flex;
        justify-content: space-around;
        align-items: center;

        .cell {
            display: flex;
            align-items: center;

            img {
                padding: 30px 0;
                max-height: 150px;
                max-width: 90px;
            }

            span {
                padding-left: 10px;
                color: white;
                text-decoration: none;
                text-transform: uppercase;
                font-weight: 600;

            }
        }
    }


}
</style>