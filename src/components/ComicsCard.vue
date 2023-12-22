<script>

export default {
    name: "ComicsCard",

    props: {
        details: Object
    }
}
</script>

<template>
    <div class="prod_card">
        <img :src="details.thumb" alt="">
        <h3>{{ details.series }}</h3>
    </div>
</template>

<style>
.prod_card {
    width: calc(100% / 6);
    padding: 20px;
    aspect-ratio: 1 / 1;

    img {
        width: 100%;
        aspect-ratio: 1 / 1;
        object-fit: cover;
        display: block;
    }

    h3 {
        padding-top: 15px;
        text-decoration: none;
        text-transform: uppercase;
        font-weight: 600;
        color: #a6a6a6;
    }


}
</style>