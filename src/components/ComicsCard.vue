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